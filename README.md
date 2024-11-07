# Student Management System

This project is a simple console-based Student Management System implemented in Java. It demonstrates CRUD (Create, Read, Update, Delete) operations using JDBC with a MySQL database.

## Features

- Add a new student
- View all students
- Update student details
- Delete a student

## Requirements

- Java Development Kit (JDK)
- MySQL Database
- MySQL JDBC Driver

## Setup

### 1. Database Setup

1. Create a MySQL database named `student_management`.
2. Create a table named `students` using the following SQL script:

```sql
CREATE DATABASE student_management;

USE student_management;

CREATE TABLE students (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100) NOT NULL,
    age INT NOT NULL,
    email VARCHAR(100) NOT NULL
);
```
## 2. Project Setup
Clone the repository.

Add the MySQL JDBC Driver (mysql-connector-java-x.x.x.jar) to your project classpath.

Update the database connection details in StudentManagementSystem.java if needed:

```java
private static final String JDBC_URL = "jdbc:mysql://localhost:3307/student_management";
private static final String JDBC_USER = "root";
private static final String JDBC_PASSWORD = "Tree@3214";
```
Running the Application
Compile the Java files:

```
javac StudentManagementSystem.java
```
Run the application:

```
java -cp .;path\to\mysql-connector-java-x.x.x.jar StudentManagementSystem
```
Usage
Follow the on-screen prompts to add, view, update, or delete students.

## 3. License
This project is licensed under the MIT License.


Feel free to customize the README as needed! If you have any questions or need further assistance, let me know! 😊

Note: For the MySQL JDBC Driver path, replace `path\to\mysql-connector-java-x.x.x.jar` with the actual path to your downloaded JDBC driver.
