# List and rate movies and series

--- 
## PHP-MySQL-Skills-Showcase
This project showcases my PHP-MySQL skills acquired during my certification. It includes practical demonstrations of key concepts and features.

---
## Table of Contents
1. Introduction
2. Prerequisites
3. Installation
4. Features
5. Future Improvements

--- 
## Introduction
This project is a web application that allows users to:

- Manage user accounts (authentication and registration).
- Create, view, edit, and delete articles.
- Perform dynamic article searches using AJAX.
- Rate and comment on articles.
- The backend is developed in PHP using PDO for data management, and the frontend utilizes HTML, CSS, and Bootstrap for a responsive user interface.

--- 
## Prerequisites
Before starting, ensure that you have the following installed on your system:

- PHP 8.0 or higher
- MySQL 5.7 or higher
- Apache or Nginx server (with PHP support)
- Composer (optional, for future dependency management)

---
## Installation
1. Clone the repository:
git clone https://github.com/your-username/project-name.git  
cd project-name  

2. Set up the database:
- Import the SQL file to create the database structure:
mysql -u root -p database_name < database.sql  

- Configure your database credentials in the config/database.php file:
<?php  
$dbHost = 'localhost';  
$dbName = 'database_name';  
$dbUser = 'root';  
$dbPass = 'your_password';  
?>  

3. Run the project:
- Place the project folder in your web server's root directory (e.g., htdocs for XAMPP).
- Access the application in your browser:
http://localhost/project-name 

---
## Features
1. Authentication:
Secure login and registration using password_hash and password_verify.

2. Article Management:
CRUD (Create, Read, Update, Delete) operations for articles.

3. Rating System:
Users can rate each article on a scale of 1-5.

4. Dynamic Search:
Real-time article search powered by AJAX.

--- 
## Future Improvements
- Implement a dynamic router to replace static URLs.
- Add automated testing (PHPUnit).
- Enhance security (CSRF tokens, input validation with a library).
- Add multi-language support for the user interface.

--- 
## License
This project is licensed under the MIT License. See the LICENSE file for details.

---
Feel free to adapt this template to fit your project’s specifics. 🎉

