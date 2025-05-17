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

