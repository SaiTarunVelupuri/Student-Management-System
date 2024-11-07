Student Management System
A simple Java-based application for managing student information, using MySQL as the database. This project allows users to add, view, update, and delete student records. It demonstrates the use of Java JDBC to interact with a MySQL database and basic console-based user interaction.

Table of Contents
Features
Technologies Used
Requirements
Setup Instructions
Usage
Database Structure
Contributing
License
Features
Add Student: Insert a new student’s name, age, and email into the database.
View Students: Display a list of all students currently in the database.
Update Student: Modify an existing student’s information.
Delete Student: Remove a student’s record from the database.
Technologies Used
Java: Programming language for the application logic.
JDBC: Java Database Connectivity for database interactions.
MySQL: Database to store student information.
MySQL Command Line Client: For managing the database directly.
VS Code: IDE for writing and managing code.
Requirements
Java Development Kit (JDK): Version 8 or higher.
MySQL: Database server, with MySQL Command Line Client 9.0.
MySQL JDBC Driver: Ensure the MySQL Connector/J .jar file is in your project’s library path.
VS Code: IDE for developing the application.
Setup Instructions
Step 1: Clone the Repository
Clone this repository to your local machine:



git clone https://github.com/SaiTarunVelupuri/Student-Management-System.git
cd Student-Management-System
Step 2: Configure the MySQL Database
Open your MySQL Command Line Client and log in with your credentials.

Create a new database for the project:

sql

CREATE DATABASE student_management;
Switch to the new database:

sql

USE student_management;
Create the students table:

sql

CREATE TABLE students (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(50) NOT NULL,
    age INT NOT NULL,
    email VARCHAR(100) NOT NULL
);
Step 3: Update Database Credentials
In the StudentManagementSystem.java file, update the database credentials in the following section:

Contributing
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Any suggestions or improvements are welcome!
