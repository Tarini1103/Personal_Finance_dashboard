# 💰 Personal Finance Dashboard

A secure and user-friendly personal finance dashboard built with **Streamlit**, **SQLAlchemy**, **Fernet encryption**, and **SHA-256 hashing**. Users can register and log in securely, track income and expenses, set monthly budgets, and create encrypted backups and restore them.

---

## 🚀 Features

- 🔐 **Secure Login/Registration**
  - SHA-256 hashed & salted passwords
  - Account lockout after repeated failed attempts

- 📊 **Financial Tracker**
  - Add encrypted income and expense entries
  - Filter, visualize, and download reports

- 🧮 **Budgeting**
  - Create encrypted monthly budgets per category
  - Track spending vs budgeted amount

- 🔒 **Security**
  - Uses Fernet encryption for stored data
  - Prevents brute-force and SQL injection attacks

- ☁️ **Backup & Recovery**
  - Create encrypted user-specific SQLite backups
  - Restore previous versions safely

---

## 🛠️ Technologies Used

- **Streamlit** - Web Interface
- **SQLAlchemy** - Database ORM
- **SQLite** - Database Engine
- **Fernet (cryptography)** - Data Encryption
- **hashlib (SHA-256)** - Password Hashing
- **Plotly** - Data Visualization
- **Pandas** - Data Handling

---

## 🔒 Security Approach

- **Confidentiality**: Fernet encryption for all sensitive fields
- **Integrity**: Passwords hashed with SHA-256 + salt
- **Availability**: Backup & restore support to avoid data loss

> CIA Principles, Brute Force Protection, and Timing comparisons included under the "Security" tab of the app.

---

