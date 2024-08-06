# phpAssignment.22RP02423
Assignment: Student Management System with PHP

# Student Management System

This project is a Student Management System developed using PHP and MySQL. 
It allows administrators to manage student records through a web interface, including creating, reading, updating, and deleting student information. The system also includes user authentication and session management.


## Features
- User authentication with sessions and cookies.
- CRUD operations for managing student records.
- Data validation and error handling.
- Secure login and session management.

## Requirements
- PHP 7.4 
- MySQL 

## Installation
1. **Clone the Repository**
    ```bash
    git clone https://github.com/yourusername/student-management-system.git
    cd student-management-system
    ```

2. **Set Up the Database**
    - Create a new MySQL database.
    - Import the provided SQL script to set up the necessary tables.
        ```sql
        mysql -u root -p        ```

3. **Configure the Database Connection**
    - Open the `config.php` file and update the database connection settings.
    ```php
    define('DB_SERVER', 'localhost');
    define('DB_USERNAME', 'class');
    define('DB_PASSWORD', ' ');
    define('DB_NAME', 'philemon');
    ```

4. **Install Dependencies**
    - Install PHP dependencies using Composer.

5. **Set Up the Web Server**
    - Ensure your Apache server is configured to serve the project directory.
    - Update  Apache configuration (e.g., `httpd.conf` or a site-specific config file) to point to the project's `public` directory.

## Usage
1. **Start the Server**
    - Start your Apache server and navigate to the project's URL (e.g., `http://localhost/student-management-system`).

2. **Log In**
3. **Manage Student Records**
    - Use the web interface to create, read, update, and delete student information.

## Troubleshooting
- Ensure that the database connection settings in `config.php` are correct.
- Verify that your Apache server is properly configured and running.
- Check file permissions to ensure the web server can access the project files.

## Contributing
1. Fork the repository.
2. Create your feature branch 
3. Commit my 
4. Push to the branch 
5. Open a pull request.


## Contact
For any questions related to this assignment
-Email: ydiasniyonshuti@yahoo.fr

