# Employee Attendance Record System

The Employee Attendance Record System is a simple project developed using PHP, HTML5, CSS, and JavaScript (jQuery/Ajax). This project can be a great starting point if you are developing an HRIS or a Payroll System. The project provides an insight into how a Biometrics System works and utilizes the Bootstrap framework for design.

## About the Project

The Employee Attendance Record System is designed to track and store employees' time logs for a specific company. The system has two user interfaces:

### Admin Side

- **Login Page**: Allows admin users to log in using their credentials to access the administrative side of the system, enhancing the security of the data.
  
- **Home Page**: Redirects users to this page after successful login.
  
- **Employee Page**: Lists all employees and their details, with functionalities to add, update, and delete employee information.
  
- **Attendance Page**: Lists the time logs of the employees. The administrator can delete an employee if necessary.
  
- **Users Page**: Lists all administrators who can access the admin side of the system, with functionalities to add, update, and delete administrator information.

### Client-Side

- **Time Log Page**: Where employees log their daily time records.

## Features

- Secure login system for admin users.
- CRUD operations for employees and administrators.
- Track and store daily time logs of employees.
- Responsive design using Bootstrap.

## How to Run the Project

1. Download the source code and extract the zip file.
2. Set up a local web server capable of running PHP scripts on your computer (I use XAMPP). Copy or extract the source code to the `htdocs` folder located in the XAMPP directory.
3. Open your database web server and create a new database named `attendance`.
4. Import the `attendance.sql` file located in the database folder of the extracted source code.
5. Ensure the source code is accessible by your web server.
6. Open a web browser (Chrome) and browse the application at `http://localhost/EARS/`.

### Admin Default Access

- **Username**: admin
- **Password**: admin123

To access the administrator side of the application, add `/admin/index.php` to your URL: http://localhost/EARS/admin/index.php

