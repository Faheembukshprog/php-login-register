# Login & Registration System (PHP + MySQL)

A simple login and registration system built with PHP, MySQL, HTML, CSS, and JavaScript. This project allows users to register and login as either a **User** or an **Admin**, and be redirected to role-specific dashboards.

---

## 🌟 Features

- User Registration with hashed passwords
- Secure Login using `password_verify()`
- Admin and User roles with dashboard redirection
- Session-based authentication
- Error messages using PHP sessions
- Simple and modern user interface with responsive design
- Toggle between login and register forms using JavaScript

---

## 🚀 Technologies Used

- PHP (Back-End)
- MySQL (Database)
- HTML5
- CSS3
- JavaScript
- Git & GitHub

---

## 📁 Folder Structure

📂 project-folder/
Represents the main project directory that contains all the files of your login/register system.    
│  
├─ 📄 index.php
The main page that shows the login and registration forms (UI).  

├── 📄 login_register.php
Handles the form submission logic — registering new users, logging in, setting sessions, etc.
  
├─── 📄 admin_page.php
The dashboard that logged-in admins are redirected to after logging in.
  
├──── 📄 user_page.php
The dashboard for normal users once they log in.
  
├───── 📄 logout.php
Ends the session and logs the user out.

├────── 📄 config.php
Contains the database connection code — this is where you define your host, username, password, and database.  

├─────── 🎨 style.css
Your project's stylesheet. It styles the login and registration forms, buttons, typography, etc.  

├──────── 🧠 script.js
Handles JavaScript logic, like switching between the login and register forms with a button.  

└───────── 📘 README.md
The documentation file (you're working on now) that explains the project, how to use it, and how it’s structured.    


---

## 🔧 Setup Instructions

1. Clone the repository:
   ```bash
   https://github.com/Faheembukshprog/php-login-register.git

 ---

2. Create a MySQL database

    * Name it user_db or update config.php with your custom database name.

3. Create the users table
Run the following SQL command:

  ```sql
CREATE TABLE users (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(100) NOT NULL,
  email VARCHAR(100) NOT NULL UNIQUE,
  password VARCHAR(255) NOT NULL,
  role ENUM('admin', 'user') NOT NULL
);
  ```


4. Update database credentials
Edit config.php to match your local setup:

```php
<?php
$host = "localhost";
$user = "root";
$password = "";
$database = "user_db";
?>
```
5. Run the project

  * Place the project folder in your local server directory (htdocs for XAMPP).

  * Visit: http://localhost/project-folder/
---
  
  

## 👤💻 Author
GitHub: Faheembukshprog(**#MrMiny**)
  
  
---
  
  
## 📜 🪪 License
This project is open source and available under the MIT License.
  
  
  
---


