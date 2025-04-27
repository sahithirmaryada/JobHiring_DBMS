# JobHiring_DBMS
 We have built a Database Management System that keeps job and user data available, using MySQL and PHP.

## Prerequisites
Ensure the following are installed on your machine before proceeding:
Git, PHP(Xampp), MySQL

## Setup Instructions

1. Clone the Repository
    git clone https://github.com/user/JobHiring_DBMS.git
    cd JobHiring_DBMS

2. Extract Application Files
The project portal is packaged in JobHiring_Portal.zip. Unzip it into your web server’s root directory:
    unzip JobHiring_Portal.zip -d /path/to/your/webroot/JobHiring_Portal

3. Database Setup
> Start your MySQL server.
> Create a new database:
    CREATE DATABASE jobhiring_db;
> Import the provided schema (assumes schema.sql is inside the extracted portal directory):
    mysql -u <username> -p jobhiring_db < /path/to/JobHiring_Portal/schema.sql

## Steps to Run the Project
PHP Built-in Server
From the portal directory: php -S localhost:8000
Access the application at http://localhost:8000
