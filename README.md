# 👨‍💼 Employee Registration System

## Overview

The **Employee Registration System** is a desktop application developed in **C# using Windows Forms and Entity Framework Core**. The system is designed to manage employee records efficiently by providing functionalities such as adding, updating, deleting, and viewing employee information stored in a SQL Server database.

This project demonstrates the implementation of **CRUD (Create, Read, Update, Delete)** operations along with database connectivity using **Entity Framework Core (Code First Approach)**. It follows Object-Oriented Programming (OOP) principles and provides a user-friendly interface for managing employee data.

---

## Features

### ➕ Add Employee

Users can add new employee records by entering:

* Employee ID
* Name
* Father Name
* CNIC
* Designation
* Salary
* Department
* Hire Date

### ✏️ Update Employee

Modify existing employee information and save the changes directly to the database.

### ❌ Delete Employee

Remove employee records from the system using the employee ID.

### 📋 View Employees

Display all employee records in a DataGridView for easy management and monitoring.

### 🗄 Database Integration

Employee data is stored permanently in a SQL Server database using Entity Framework Core.

---

## Technologies Used

* **Programming Language:** C#
* **Framework:** .NET Framework / Windows Forms
* **Database:** SQL Server
* **ORM:** Entity Framework Core
* **Architecture:** OOP-Based Design

---

## OOP Concepts Implemented

### Encapsulation

Employee data and database operations are organized into classes.

### Abstraction

Database operations are simplified through Entity Framework Core.

### Modularity

The project separates user interface logic from database management logic.

### Reusability

Classes can be extended and reused for future enhancements.

---

## Database Structure

### Employee Table

| Field       | Description              |
| ----------- | ------------------------ |
| Id          | Unique Employee ID       |
| Name        | Employee Name            |
| FatherName  | Employee's Father Name   |
| CNIC        | National Identity Number |
| Designation | Employee Job Title       |
| Salary      | Monthly Salary           |
| Department  | Assigned Department      |
| HireDate    | Date of Hiring           |

---

## Functionalities

* Create Employee Records
* Read Employee Records
* Update Employee Information
* Delete Employee Records
* Display Employee List
* SQL Server Database Connectivity
* Entity Framework Core Integration

---

## Learning Outcomes

Through this project, I gained practical experience in:

* Windows Forms Application Development
* Entity Framework Core
* SQL Server Database Management
* CRUD Operations
* Database Connectivity
* Object-Oriented Programming
* Event-Driven Programming

---

## Future Enhancements

* Employee Search Functionality
* Department Management Module
* Attendance Tracking System
* Payroll Management
* Authentication & Role-Based Access
* Employee Performance Evaluation
* Report Generation

---

## Conclusion

The Employee Management System provides a simple and efficient solution for managing employee records. By integrating Windows Forms with SQL Server through Entity Framework Core, the application demonstrates real-world database operations while applying OOP principles and modern data-access techniques.
