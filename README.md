# Secure Login System

A secure web-based authentication system built using Flask, SQLite, and Bcrypt. This project provides user registration, login, session management, password hashing, and protection against common security threats such as SQL Injection.

## Features

* User Registration
* User Login Authentication
* Secure Password Hashing using Bcrypt
* Session Management
* Logout Functionality
* SQLite Database Integration
* SQL Injection Protection using Parameterized Queries
* Input Validation
* Responsive User Interface with CSS
* Easy to Extend with Two-Factor Authentication (2FA)

## Technologies Used

* Python
* Flask
* Flask-Bcrypt
* SQLite
* HTML
* CSS

## Project Structure

```text
project4/
│
├── app.py
│
├── users.db
│
├── static/
│   └── style.css
│
└── templates/
    ├── login.html
    ├── register.html
    └── dashboard.html
```

## Installation

### 1. Clone the Repository

```bash
git clone <repository-url>
cd project4
```

### 2. Install Required Packages

```bash
pip install flask flask-bcrypt
```

### 3. Run the Application

```bash
python app.py
```

### 4. Open in Browser

```text
http://127.0.0.1:5000
```

## How It Works

### Registration

* User enters a username and password.
* Password is hashed using Bcrypt before storage.
* User data is saved in the SQLite database.

### Login

* User enters credentials.
* System verifies the hashed password.
* Successful authentication creates a user session.

### Dashboard

* Accessible only to authenticated users.
* Displays user information after login.

### Logout

* Session data is cleared.
* User is redirected to the login page.

## Security Features

### Password Hashing

Passwords are never stored in plain text.

### SQL Injection Prevention

Parameterized SQL queries are used to prevent injection attacks.

### Session Management

User sessions are securely maintained until logout.

### Input Validation

Basic validation is applied to usernames and passwords.

## Future Enhancements

* Two-Factor Authentication (2FA)
* Email Verification
* Password Reset Functionality
* Password Strength Meter
* User Profile Management
* Dark Mode Interface

## Learning Outcomes

This project demonstrates:

* Web Application Development with Flask
* Authentication and Authorization
* Database Integration
* Secure Password Storage
* Session Handling
* Cybersecurity Best Practices

## Author

Nikku Goswami

B.Tech Data Science Student

## License

This project is created for educational and learning purposes.
