# 🏨 ROOM207 - Hotel Management System (Backend)

![Project Status](https://img.shields.io/badge/Status-Development-green)
![Backend](https://img.shields.io/badge/Backend-Flask-lightgrey)
![Database](https://img.shields.io/badge/DB-SQL%20Server-red)
![Security](https://img.shields.io/badge/Security-Protected-blue)

**ROOM207** is a robust Hotel Management System backend. It provides a RESTful API to manage hotel operations including guest registration, room availability, and booking management using Python and SQL Server.

## 🚀 Key Features
- **Guest Management:** Full CRUD operations for managing guest profiles.
- **Room Tracking:** Real-time monitoring of room status and categories.
- **Secure Database Connection:** Uses `pyodbc` with environment variables for secure SQL Server integration.
- **CORS Enabled:** Ready to be connected with any Frontend framework (React, Vue, etc.).

## 🛠 Tech Stack
- **Framework:** Flask
- **Language:** Python 3.x
- **Database:** Microsoft SQL Server
- **Driver:** pyodbc (ODBC Driver 17)
- **Environment Management:** python-dotenv

## 📦 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/rowannhussein86/ROOM207-.git](https://github.com/rowannhussein86/ROOM207-.git)
   cd ROOM207-

## 📂 Project Structure

```bash
ROOM207/
│
├── ER_Diagram/              # Entity Relationship Diagram
├── Mapping/                 # ER to Relational Mapping
├── Queries/                 # SQL queries
│   ├── SQLQuery1.sql
│   ├── SQLQuery2.sql
│   └── SQLQuery3.sql
├── templates/               # HTML templates
│   └── Frontend.html
├── connection.ipynb         # Database connection & testing notebook
├── .env                     # Environment variables (local only)
└── .gitignore               # Files excluded from version control
```

├── requirements.txt    # Project dependencies
└── README.md           # Project documentation
