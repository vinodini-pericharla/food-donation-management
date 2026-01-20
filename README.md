Food Donation Management System 

A web-based application to manage food donation workflows by connecting donors, admin, and delivery agents. It allows users to submit food donation requests, helps admins manage and track donations, and supports delivery coordination.

Features
Donor / User

Register & Login

Submit food donation request

View donation details

Admin Module

Admin login dashboard

Manage donation requests

View feedback and analytics

Delivery Module

Delivery agent login/signup

View assigned orders

Location/map support

Additional

Chatbot support

Email notifications using PHPMailer

Tech Stack

Frontend: HTML, CSS, JavaScript

Backend: PHP

Database: MySQL

Mailer: PHPMailer

Project Modules

admin/ – Admin dashboard & donation management

delivery/ – Delivery agent workflows

chatbot/ – Chatbot UI + scripts

database/ – SQL file (demo.sql)

phpmailer/ – Email sending module

Installation & Setup (XAMPP)
Requirements

XAMPP / WAMP / LAMP

PHP 7+

MySQL

Steps

Copy project folder into:

C:\xampp\htdocs\donate\


Start Apache and MySQL in XAMPP.

Import database:

Open phpMyAdmin

Create a DB (example: donate_db)

Import:

database/demo.sql


Update database config in:

connection.php

admin/connect.php

delivery/connect.php

Example:

$host = "localhost";
$user = "root";
$password = "";
$dbname = "donate_db";


Run the project in browser:

http://localhost/donate/

Useful Links

User Module: http://localhost/donate/

Admin Login: http://localhost/donate/admin/login.php

Delivery Login: http://localhost/donate/delivery/deliverylogin.php

Author

Vinodini Pericharla
GitHub: https://github.com/vinodini-pericharla
