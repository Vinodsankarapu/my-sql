##  Day 1 Complete
Day 1: Added Full Stack Development basics including Frontend, Backend, APIs, Storage Areas, FMS, and DBMS concepts.
## Day 2 complete
Day 2: Added DBMS concepts including FMS vs DBMS, database fundamentals, client-server architecture, and data models.
## Day 3 - SQL Basics Completed
Learned SQL Identifiers and naming rules.
Studied SQL fundamentals.
Covered SQL command categories: DDL, DML, DCL, TCL, and DQL.
Understood the purpose of commands like CREATE, ALTER, DROP, TRUNCATE, INSERT, UPDATE, DELETE, COMMIT, ROLLBACK, SAVEPOINT, GRANT, REVOKE, and SELECT.

## day 4 - SQL data definition language(DDL)
# MySQL ALTER TABLE Practice

This repository contains MySQL Data Definition Language (DDL) practice queries focused on the `ALTER TABLE` command. It demonstrates how to modify table structures using different SQL operations.

## 📌 Topics Covered

- Create Database
- Create Table
- Add Columns
- Modify Column Data Types
- Rename Columns
- Drop Columns
- Rename Tables
- Change Column Position (FIRST, AFTER)
- Practice with EMPLOYEES and COMPANY_STAFF tables

## 🛠️ SQL Operations Used

- CREATE DATABASE
- USE DATABASE
- CREATE TABLE
- ALTER TABLE ADD COLUMN
- ALTER TABLE MODIFY
- ALTER TABLE CHANGE
- ALTER TABLE DROP COLUMN
- ALTER TABLE RENAME TO
- DESC TABLE
- SHOW TABLES

## 🎯 Learning Objectives

- Understand MySQL DDL commands.
- Learn how to modify existing database tables.
- Practice real-world table structure updates.
- Improve SQL database management skills.

## 💻 Technologies Used

- MySQL
- MySQL Workbench

  # MySQL DML Practice day -5
  
This repository contains my MySQL Day-5 practice on **Data Manipulation Language (DML)** commands. It includes syntax, examples, common errors, and query outputs for learning and interview preparation.

## 📚 Topics Covered

- INSERT
  - Insert single record
  - Insert multiple records
  - Insert with selected columns
  - INSERT ... SET syntax

- UPDATE
  - Update single column
  - Update multiple columns
  - Update records using WHERE clause

- DELETE
  - Delete specific records
  - Delete using conditions

## 🛠️ Technologies Used

- MySQL
- SQL (DML Commands)

## 📂 Contents

- INSERT statement examples
- UPDATE statement examples
- DELETE statement examples
- Sample Employee table
- MySQL syntax errors and their fixes
- Query execution results

## 🎯 Learning Outcomes

- Understand DML operations in MySQL.
- Practice inserting, updating, and deleting records.
- Learn to identify and fix common SQL syntax errors.
- Improve SQL query writing skills.

# MySQL DCL day - 6

This repository contains MySQL practice examples covering:

- Creating databases and tables
- AUTO_INCREMENT and generated columns
- INSERT, UPDATE, SELECT operations
- Creating backup tables
- CREATE USER and user authentication
- GRANT and REVOKE privileges
- Testing user permissions
- Common SQL syntax and permission errors

- # 📘 Day 7 – SQL Transaction Control Language (TCL) & Locking

## 📌 Overview

On Day 7, I learned **Transaction Control Language (TCL)** commands and **database locking mechanisms** in MySQL. These concepts are essential for managing database transactions, maintaining data integrity, and controlling concurrent access to data.

## 📚 Topics Covered

### Transaction Control Language (TCL)

* START TRANSACTION
* COMMIT
* ROLLBACK
* SAVEPOINT

### Locking Mechanisms

* Shared Lock
* Exclusive Lock
* Intent Lock
* READ Lock
* WRITE Lock
* LOCK TABLES
* UNLOCK TABLES

## 💻 Practical Exercises

* Created and managed database transactions.
* Used **COMMIT** to permanently save changes.
* Used **ROLLBACK** to undo transactions.
* Created **SAVEPOINTS** and rolled back to specific points.
* Practiced table locking using **READ** and **WRITE** locks.
* Learned how locks prevent data conflicts when multiple users access the same table.

## 🎯 Key Learnings

* Understood the purpose of database transactions.
* Learned how TCL commands ensure data consistency.
* Explored different types of locks and their use cases.
* Gained hands-on experience with transaction management in MySQL.

## 🛠️ Technologies Used

* MySQL
* SQL (TCL Commands)

  # 📘 Day 8 – SQL Constraints

## 📌 Overview

On **Day 8**, I learned about **SQL Constraints** in MySQL. Constraints are rules applied to table columns to ensure that only valid, accurate, and consistent data is stored in the database.

## 📚 Topics Covered

### What are Constraints?

Constraints are rules that control the data entered into a table. They help maintain the accuracy and integrity of the database.

### Why Do We Use Constraints?

* Maintain data integrity
* Prevent invalid data entry
* Avoid duplicate records
* Ensure relationships between tables
* Make the database reliable and consistent

## 🛠️ Types of Constraints

### 1. NOT NULL

* Prevents `NULL` values from being stored in a column.

### 2. UNIQUE

* Ensures that all values in a column are unique.
* Duplicate values are not allowed.

### 3. PRIMARY KEY

* A combination of **NOT NULL** and **UNIQUE**.
* Uniquely identifies each record in a table.

### 4. COMPOSITE KEY

* A primary key made up of **two or more columns**.
* Used when a single column cannot uniquely identify a record.

### 5. FOREIGN KEY

* Creates a relationship between two tables.
* References the **Primary Key** of another table.
* The table containing the foreign key is called the **Child Table**.
* The referenced table is called the **Parent (Referenced) Table**.

### 6. CHECK

* Restricts the values that can be entered into a column.
* Ensures that only values satisfying a specified condition are accepted.

### 7. DEFAULT

* Automatically assigns a predefined value to a column if no value is provided during an `INSERT` operation.

## 🔗 Referential Actions

Referential actions define what happens to child table data when parent table data is updated or deleted.

* **ON DELETE CASCADE**
* **ON UPDATE CASCADE**
* **ON DELETE SET NULL**
* **ON UPDATE SET NULL**

## 💻 Practical Learning

* Applied different SQL constraints while creating tables.
* Understood how constraints improve data accuracy.
* Practiced creating relationships using Foreign Keys.
* Explored referential actions to maintain consistency between related tables.

## 🛠️ Technologies Used

* MySQL
* SQL


# MySQL DAY - 9:

This repository contains my MySQL practice programs and exercises. It covers SQL fundamentals, CRUD operations, arithmetic operators, comparison operators, logical operators, and conditional queries using sample databases.

## Topics Covered

- Database and Table Creation
- INSERT Records
- SELECT Queries
- Arithmetic Operators
  - Addition (+)
  - Subtraction (-)
  - Multiplication (*)
  - Division (/)
  - Modulus (%)
- Comparison Operators
  - =
  - !=
  - <>
  - >
  - <
  - >=
  - <=
- Logical Operators
  - AND
  - OR
  - NOT
- UPDATE Statements
- DELETE Statements
- DROP TABLE
- Query Aliases (AS)
- Conditional Filtering (WHERE)

## Practice Tables

### Products
- Product inventory management
- Price calculations
- Inventory value calculations
- Quantity updates
- Product deletion based on conditions

### StudentScores
- Student marks analysis
- Filtering students using comparison operators
- Updating marks based on conditions
- Deleting records using WHERE clause

### Employees
- Employee management
- Department-wise filtering
- Salary updates
- Active/Inactive employee management
- Logical operator practice

## SQL Concepts Practiced

- CREATE TABLE
- INSERT INTO
- SELECT
- UPDATE
- DELETE
- DROP TABLE
- WHERE
- AS
- Arithmetic Expressions
- Comparison Operators
- Logical Operators

## Tools Used

- MySQL 8.x
- MySQL Command Line Client

## Learning Outcome

Through this practice, I learned how to:
- Create and manage tables
- Perform CRUD operations
- Write efficient SELECT queries
- Apply arithmetic calculations in SQL
- Use comparison and logical operators
- Update and delete records based on conditions
- Work with real-world sample data



