# 🏧 ATM Interface System

A Java-based ATM Interface developed as part of the Oasis Infobyte Java Development Internship Program. The project simulates the basic functionalities of an Automated Teller Machine (ATM) including user authentication, balance inquiry, cash withdrawal, cash deposit, and transaction management.

## 📌 Project Overview

This application provides a simple ATM simulation where users can securely log in using their Account Number and PIN. After successful authentication, users can perform banking operations such as checking balance, depositing money, and withdrawing money.

The project is built using Java for backend logic, HTML/CSS for the user interface, and MySQL for database connectivity.

---

## ✨ Features

- 🔐 Secure Login Authentication
- 💰 Balance Inquiry
- ➕ Deposit Money
- ➖ Withdraw Money
- 🗄️ MySQL Database Connectivity
- 🎨 User-Friendly Interface
- ⚡ Fast and Simple Operations

---

## 🛠️ Technologies Used

- Java
- MySQL
- HTML
- CSS
- JDBC (Java Database Connectivity)

---

## 📂 Project Structure

```text
AnjaliThakur_Task3_ATM

│
├── backend
│   ├── ATM.java
│   ├── DBConnection.java
│
├── frontend
│   ├── index.html
│   ├── style.css
│
├── lib
│   └── mysql-connector-j-9.7.0.jar
│
└── README.md
```

---

## 🚀 How to Run the Project

### Step 1: Clone the Repository

```bash
git clone <repository-url>
```

### Step 2: Open the Project

Open the project folder in VS Code or any Java IDE.

### Step 3: Configure MySQL Database

Create a database:

```sql
CREATE DATABASE atm_project;
```

Create the required table and insert sample records.

### Step 4: Compile the Java Files

```bash
javac backend\ATM.java
javac backend\DBConnection.java
```

### Step 5: Run the Application

```bash
java backend.ATM
```

### Step 6: Login Credentials

```text
Account Number : 12345678
PIN            : 1234
```

### Step 7: Launch Frontend

Open:

```text
frontend/index.html
```

in any web browser.

---

## 📸 Sample Functionalities

- User Login
- Check Balance
- Deposit Amount
- Withdraw Amount
- Exit System

---

## 🎯 Learning Outcomes

Through this project, I learned:

- Core Java Programming
- JDBC Connectivity
- Database Integration
- Frontend Development using HTML & CSS
- Project Structure and GitHub Management

---

## 👩‍💻 Author

**Anjali Thakur**

B.Tech (Computer Science Engineering)

---

## 🏢 Internship

**Oasis Infobyte (OIBSIP) – Java Development Internship**

---

⭐ If you found this project useful, feel free to explore the repository.