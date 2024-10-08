# SQL Mini Projects
This repository contains a collection of small SQL projects that demonstrate the creation and management of various databases using SQL. Each .sql file contains the necessary SQL commands to create tables, insert data, and perform basic operations related to different management systems.

## Projects Overview
### 1. Library Management System
File: Library Management.sql

This project simulates a library management system where you can track:

Authors: Basic details of authors whose books are available in the library.
Books: Information on available books including their title, author, and publication year.
Book Loans: Records of book loans, including borrower details and the loan/return dates.
Key SQL Concepts:
CREATE TABLE, INSERT INTO, and SELECT
Foreign key relationships to link books and authors
Querying loans based on dates and borrower information

### 2. Railway System Management
File: Railway system.sql

This project models a simple railway management system where you can:

Stations: Manage different stations in the system.
Trains: Track trains running between stations with their schedules.
Passengers: Record passenger information and their ticket bookings.
Key SQL Concepts:
Schema design for trains, stations, and passengers
Joining data between trains and passenger bookings
Use of primary and foreign keys to enforce relationships


### 3. Sales and Customer Tracking System
File: sales and customer.sql

This project focuses on managing:

Customers: Basic customer details such as name and email.
Products: A catalog of products available for purchase, with pricing information.
Sales: Records of sales transactions, including the customer, product purchased, quantity, and sale date.
Key SQL Concepts:
Managing sales data using foreign key relationships
Aggregate queries to calculate total sales or quantity sold
Tracking customer purchases over time


### 4. Student Management System
File: student Management system.sql

This project models a basic student management system where:

Students: Records of student details such as name, age, and enrollment date.
Courses: A list of available courses with course codes and instructor details.
Enrollments: The courses students are enrolled in, tracked by enrollment date.
Key SQL Concepts:
Using relational tables to manage students, courses, and enrollments
Aggregating data to calculate enrollment counts
Querying course enrollments based on student and course IDs
How to Use
Download the desired .sql file.
Execute the SQL script in any SQL database management system (e.g., MySQL, PostgreSQL, or SQLite).
Review the database schema and sample data created by the script.
Run queries to test the functionality of the system.

### 5.E-Commerce Order Management System

This project is a simple e-commerce order management system built using SQL. It allows you to manage customers, products, orders, and shipping details. The database schema is designed to simulate an online store where customers can place orders, and orders can contain multiple products.

#### Database Schema
The system is made up of the following tables:
1. **Customers**: Stores customer details.
2. **Products**: Stores available products with pricing and stock.
3. **Orders**: Stores order details, linked to customers.
4. **Order_Items**: Manages the products included in each order.
5. **Shipping**: Tracks shipment information for each order.

#### Features
- Multiple orders per customer.
- Ability to track product stock and adjust it based on purchases.
- Order statuses (e.g., pending, shipped, delivered).
- Shipment tracking with delivery details.

#### How to Use
1. Download the `.sql` file.
2. Execute the script in your database management system (e.g., MySQL, PostgreSQL, SQLite).
3. Insert sample data for testing or create your own test data.
4. Run queries to manage customers, view orders, and track shipments.

#### Example Queries
- View all orders placed by a customer.
- Check products in a specific order.
- Track the shipping status of an order.

## License
Feel free to use or modify this project for educational or personal purposes.

