# Employee Attendance Record System

The Employee Attendance Record System is a web application created using PHP, HTML5, CSS, and JavaScript (jQuery/Ajax). This project was undertaken as part of my practicum to showcase my web development skills.

## Project Overview

The Employee Attendance Record System is a tool designed to manage and archive employees' daily attendance for a particular company. The system offers two main interfaces:

### Admin Interface

- **Login**: Admins can securely log in with their credentials to access the system.
  
- **Home**: After a successful login, the admin is redirected to the dashboard.
  
- **Employee Management**: This page displays a list of all employees with options to add, edit, or remove their details.
  
- **Attendance Log**: Admins can view and manage the time logs of the employees, with the ability to delete records if necessary.
  
- **User Management**: This section lists all admin users with options to add, edit, or remove their details.

### Employee Interface

- **Time Logging**: Employees can log their daily working hours.

## Key Features

- Secure login mechanism for admin users.
- CRUD (Create, Read, Update, Delete) operations for managing employees and admin users.
- Automatic tracking and storage of daily attendance records.
- Mobile-responsive design using Bootstrap.

## Installation Guide

1. Download and extract the project source code.
2. Install a local web server that supports PHP (I used XAMPP). Place the source code in the `htdocs` folder of your XAMPP installation.
3. Create a new database named `attendance` in your database server.
4. Import the `attendance.sql` file from the database folder into the newly created `attendance` database.
5. Ensure that the source code is accessible through your web server.
6. Open Chrome and navigate to `http://localhost/EARS/` to access the application.

### Admin Login Details

- **Username**: admin
- **Password**: admin123

To access the admin panel, append `/admin/index.php` to the base URL: http://localhost/EARS/admin/index.php
