# Library Management System

A PHP-based library management system built with CodeIgniter. The project is designed to manage library resources, including students, departments, authors, books, and issued book records.

## Author

Navneet Tyagi

## Project Overview

This project provides a basic library management workflow for:

- Managing student records
- Managing departments
- Managing authors
- Managing books
- Issuing books to students
- Viewing student and book details
- Tracking book issue records

The application follows the standard CodeIgniter MVC structure and uses a MySQL database connection configured in the project.

## Technology Stack

- PHP
- CodeIgniter 3
- MySQL
- Apache / Nginx web server

## Project Structure

- `application/controllers/` - Controller logic for pages and actions
- `application/models/` - Database model classes
- `application/views/` - UI templates and page layouts
- `application/config/` - Configuration files, including database and routing
- `system/` - CodeIgniter framework core files
- `tests/` - Test-related files

## Default Configuration

The application is configured to use a MySQL database named `db_code` with the default local setup:

- Host: `localhost`
- Username: `root`
- Password: `password`

Update these values in `application/config/database.php` if your local environment differs.

## Setup Instructions

1. Install PHP and Apache/Nginx.
2. Install MySQL and create the required database.
3. Clone the project to your local web server directory.
4. Configure the database settings in `application/config/database.php`.
5. Set the base URL in `application/config/config.php`.
6. Start the web server and open the project in the browser.

Example local URL:

```bash
http://localhost/PHP_CodeIgniterProject/
```

## Default Route

The application is configured to load the `library` controller by default.

## Notes

This repository contains both the CodeIgniter framework files and the custom project logic for the library management system. Before using the application, ensure that the required database tables and related records exist for the modules used by the project.
