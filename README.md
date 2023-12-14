# Vehicle Parking Management System (VPMS) Project

## Overview

The Vehicle Parking Management System (VPMS) is a web-based application developed using PHP and MySQL to efficiently manage vehicle parking. This system facilitates easy parking space allocation, tracking, and user management for improved parking operations.

## Installation Instructions

Follow these steps to set up and run the VPMS project on your local server:

1. **Download the Project:**
    - Download the project zip file from the repository.

2. **Extract and Copy:**
    - Extract the downloaded file and copy the `vpms` folder.

3. **Paste in Root Directory:**
    - Paste the `vpms` folder inside your web server's root directory:
        - For XAMPP: `xampp/htdocs`
        - For WAMP: `wamp/www`
        - For LAMP: `var/www/html`

4. **Database Setup:**
    - Open PHPMyAdmin (http://localhost/phpmyadmin).
    - Create a new database named `vpmsdb`.
    - Import the database schema by executing the SQL script `vpmsdb.sql` (found in the SQL file folder within the downloaded zip package).

5. **Run the Application:**
    - Access the application by navigating to http://localhost/vpms in your web browser.

6. **Login Credentials:**

    - **Admin:**
        - Username: admin
        - Password: Test@123

    - **User:**
        - Username: 1234567890
        - Password: Test@123

    - Alternatively, you can register a new user.

## Important Note

Ensure that your web server (XAMPP, WAMP, or LAMP) is running before accessing the application.

Feel free to explore and customize the application based on your requirements.

Happy parking management!
