# PHP Login System

This is a PHP-based login system that enables users to register, log in, and log out securely. It's built with PHP for server-side scripting, HTML for structure, CSS for styling, and MySQL for the database.

## Features

- **User Registration**: New users can create accounts with unique usernames and strong passwords.
- **User Login**: Registered users can securely log in to their accounts.
- **Logout Functionality**: Users can securely log out of their accounts.
- **Data Validation**:
  - Username Validation: Ensures usernames are unique and meet specified criteria.
  - Password Validation: Enforces password strength requirements.
  - Input Sanitization: Protects against SQL injection and other forms of malicious input.

## Setup

### Prerequisites

Before you begin, ensure you have the following installed on your system:

- Web server (e.g., Apache, Nginx)
- PHP (version >= 7.0)
- MySQL (or any other compatible database)

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/SyedBilalDeveloper/Login-System-with-PHP.git
   ```

2. **Database Setup**:
   - Create a MySQL database.
   - Import the `user-registration.sql` file to set up the necessary tables.

3. **Configuration**:
   - Open `lib\DataSource.php`.
   - Update the database connection details.

4. **Run the Application**:
   - Ensure your web server and MySQL server are running.
   - Navigate to the project directory using your web browser.

## Usage

1. **Registration**:
   - Navigate to the registration page.
   - Enter a unique username and a strong password.
   - Submit the form to create a new account.

2. **Login**:
   - Navigate to the login page.
   - Enter your username and password.
   - Submit the form to log in to your account.

3. **Logout**:
   - Click on the logout button to securely log out of your account.

## Contributing

Contributions are welcome! If you'd like to improve this login system, please fork the repository and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
