# 🛡️User Authentication & Authorization System — Secure Access Management

A secure, **modular** authentication and authorization system built with **Python**, **Flask**, **SQLite**, and **JWT**.  
It supports user registration, login, role-based access control, and permission management for protected APIs.  
Designed for easy deployment locally or on cloud platforms (e.g. Colab, Heroku).

---

## 🗄️ Features

- **User registration and login** with secure password hashing  
- **JWT-based authentication** with token expiration  
- **Role-based access control** (User, Admin)  
- **Permission management** (read, write, delete, admin)  
- **SQLite database** for lightweight, zero-configuration storage  
- **Modular design** for scalability and maintainability  

---

## 📌 Project Highlights

- **Backend Implementation**: Flask-based REST API with distinct layers for routes, auth logic, and database models  
- **Security Measures**: Bcrypt password hashing, JWT tokens, prevention of SQL injection, and input validation  
- **Database Design**: Entities for users, roles, permissions, with default mappings for user and admin  
- **Testing & Usage**: Automated tests covering key functionality; manual testing via Postman or Python `requests`  
- **Deployment Ready**: Works locally or can be deployed on Colab, Heroku, Railway, etc., using environment variables for configuration  

---

## 🗂️ Project Structure

User-Auth-System/
├── main.py                 # Entry point of the application
├── config.py               # App & database configuration (secret keys, JWT setup)
├── models.py               # SQLite ORM models (User, Role, Permission)
├── auth.py                 # Authentication & authorization logic (JWT handling)
├── routes.py               # API route definitions
├── utils.py                # Helper functions (validators, decorators)
├── requirements.txt        # Dependencies
├── tests/                  # Unit tests
│   └── test_auth.py
├── docs/                   # Documentation (ERD, setup guide, etc.)
│   └── ERD.png
└── README.md

