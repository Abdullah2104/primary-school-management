# Primary School Management System

A PHP & MySQL web application for **ছত্রপুর সরকারি প্রাথমিক বিদ্যালয় (Chatrapur Government Primary School)**, with a public website and separate portals for admins, teachers and students.


## Features

- **Public site:** home page with notice board, about us, teacher list, feedback form
- **Admin:** manage notices (PDF), students (Excel import), teachers, school info and feedback; email teachers
- **Teacher:** edit profile, view class, upload results from Excel, export student list
- **Student:** log in with class + roll, view profile, results and academic calendar

## Tech Stack

PHP, MySQL/MariaDB, Bootstrap, jQuery, SpreadsheetReader, FullCalendar, Sendinblue API

## Setup

1. Copy the project to `xampp/htdocs/`.
2. In phpMyAdmin, run `SET GLOBAL max_allowed_packet=300000000;`, create a database named `pschool`, and import `readme/Master.sql`.
3. Set your database credentials in `partial/connection.php`.
4. Start Apache and MySQL, then open `http://localhost/primary-main/home/homePage.php`.


