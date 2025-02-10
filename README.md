# Blood-Bank-Managment-System
# Blood Bank Management System (BBMS)

## Project Description
The **Blood Bank Management System (BBMS)** is a web-based application designed to manage blood donations, donor registrations, and blood stock levels efficiently. It enables users to register as donors, request blood, and manage blood stock details. The admin panel provides functionalities to monitor and update blood availability.

## Features
- User registration and login
- Donor registration and listing
- Blood stock management
- Blood exchange requests
- Admin panel for monitoring and updates
- Secure authentication and session management

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- **Styling & Interactivity:** CSS, JavaScript

## Prerequisites
Before running the project, ensure you have the following installed:
1. **XAMPP** (or any other Apache & MySQL server)
2. **PHP (7.x or later)**
3. **MySQL Database**
4. **A Web Browser (Chrome, Firefox, Edge, etc.)**

## Steps to Run the Project
### 1. Setup XAMPP (or any PHP server)
- Download and install [XAMPP](https://www.apachefriends.org/index.html)
- Start the **Apache** and **MySQL** services in XAMPP Control Panel

### 2. Configure the Project Files
- Copy the **bbms** folder and paste it into the `htdocs` directory inside the XAMPP installation folder (e.g., `C:\xampp\htdocs\bbms`)
- Open **phpMyAdmin** by visiting `http://localhost/phpmyadmin/`

### 3. Setup the Database
- Create a new database named **bbms**
- Open the **bbms** folder and find the SQL file (if provided)
- Import the SQL file into the `bbms` database using phpMyAdmin

### 4. Configure Database Connection
- Open the `connection.php` file inside the **bbms** folder
- Ensure the database credentials are correct:
  ```php
  $servername = "localhost";
  $username = "root";
  $password = ""; // Default password is blank in XAMPP
  $dbname = "bbms";
  ```

### 5. Run the Project
- Open a browser and visit: `http://localhost/bbms/`
- The homepage of the Blood Bank Management System should load

### 6. Login Credentials (if applicable)
- **Admin Panel:**
  - URL: `http://localhost/bbms/admin-home.php`
  - Default Username: `admin`
  - Default Password: `admin123`
- **User Login:** Users can register and log in to access donor-related features.

## How to Save Changes and Work with the Project
- To modify styles, edit files inside the **css/** folder
- To update JavaScript functionality, edit files inside the **js/** folder
- To add new features, modify **PHP** files inside the project
- Always restart Apache and MySQL services after making changes to PHP or database configurations

## Troubleshooting
- **If the database is not connecting:**
  - Check if MySQL is running in XAMPP
  - Verify database credentials in `connection.php`
- **If the website is not loading:**
  - Ensure the project folder is inside `htdocs`
  - Try accessing `http://localhost/bbms/index.php`
- **If styles or scripts are not working:**
  - Check the console for errors in the browser (F12 > Console)
  - Verify CSS and JavaScript file paths

## Future Enhancements
- Adding a blood request tracking system
- Implementing email notifications for donors
- Enhancing the UI for better user experience

---
**Developed by:** [Chaitanya G H]

