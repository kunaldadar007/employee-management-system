mployee Management System

A secure Employee Management System built using Java, JDBC, and MySQL.
This application provides REST-based backend functionality for managing employee records with authentication and role-based access control.

🚀 Features

User Registration & Login

Role-Based Access Control (Admin / User)

Employee CRUD Operations (Create, Read, Update, Delete)

Search and Filter Employees

Structured Exception Handling

Data Validation

Exportable Reports (if implemented)

Clean Layered Architecture (Controller → Service → DAO → Model)

🛠 Tech Stack

Programming Language: Java

Backend: Core Java, JDBC

Database: MySQL

API Testing: Postman

Build Tool: Maven (if used)

Version Control: Git & GitHub

📂 Project Structure
employee-management-system/
│
├── src/
│   ├── controller/
│   ├── service/
│   ├── dao/
│   ├── model/
│   └── util/
│
├── resources/
│   └── db.sql
│
└── README.md


🔐 Authentication & Authorization

Secure login system

Role-based access (Admin can manage employees, User has limited access)

Validation checks before performing operations

📌 API Endpoints (Sample)
Method	Endpoint	Description
POST	/register	Register new user
POST	/login	Authenticate user
GET	/employees	Get all employees
GET	/employee/{id}	Get employee by ID
POST	/employee	Add new employee
PUT	/employee/{id}	Update employee
DELETE	/employee/{id}	Delete employee
🗄 Database Setup

Install MySQL.

Create a database:

CREATE DATABASE employee_db;


Import the provided db.sql file.

Update database credentials inside your configuration file.

Example:

String url = "jdbc:mysql://localhost:3306/employee_db";
String username = "root";
String password = "your_password";

▶ How to Run the Project

Clone the repository:

git clone https://github.com/kunaldadar007/employee-management-system.git


Open the project in IntelliJ IDEA / Eclipse.

Configure MySQL database.

Run the main application file.

Test APIs using Postman.

🧪 Testing

Unit tests written using JUnit (if implemented)

Manual API testing performed using Postman

📈 Key Learning Outcomes

Implemented layered architecture (Controller, Service, DAO)

Hands-on experience with JDBC and database connectivity

Built secure authentication flow

Applied OOP principles and exception handling

Designed REST-style endpoints

📎 Future Enhancements

Integrate Spring Boot

Add JWT-based authentication

Deploy on cloud (AWS / Render)

Add Swagger documentation

Improve UI with React integration

👤 Author

Kunal Dadar
Java Backend Developer
GitHub: https://github.com/kunaldadar007

LinkedIn: https://linkedin.com/in/kunaldadar

📜 License

This project is for educational and portfolio purposes.

