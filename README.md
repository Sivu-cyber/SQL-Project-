Employee Management System

The Employee Management System is a SQL Server–based project to manage employees, departments, roles, and attendance. It includes functionality for data storage, attendance tracking, late arrival monitoring, automated updates via triggers, and work hour calculation using functions.

Features:

Database Setup:

Database: Emp_Project

Tables: Departments, Roles, Employees, Attendance

Auto-increment primary keys with constraints


Data Insertion:

Inserted records into Departments and Roles

Bulk inserted 200+ employee records using SQL Server’s Import Flat File option


Attendance Tracking:

Monthly attendance reports per employee

Late arrival tracking reports


Triggers:

Automatically update records when attendance is modified


Functions:

Calculate total working hours for an employee


Reports:

Department-wise average attendance using GROUP BY and HAVING




Requirements:

Database: SQL Server

Tools: SQL Server Management Studio (SSMS)

Data Source: Dummy employee dataset (Excel/CSV imported into SQL Server)


Future Enhancements:

Web UI for employee and admin accesss

Integration with biometric attendance devices

Role-based access controls

