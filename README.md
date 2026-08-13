# Restaurant Management System

A relational database system designed to support core restaurant operations including **order processing, menu management, table management, employee management, customer feedback, billing, and delivery tracking**.

## Tech Stack

* **Database:** MySQL
* **Database Design:** Relational schema, primary & foreign keys
* **SQL:** DDL, data insertion, querying and CRUD operations
* **Tools:** MySQL Workbench

## Project Structure

| File                     | Description                                                        |
| ------------------------ | ------------------------------------------------------------------ |
| `DDL.sql`                | Defines the database schema, tables, constraints and relationships |
| `test_data.sql`          | Populates the database with sample restaurant data                 |
| `relational_schema`      | Visual representation of the database relationships                |
| `Project_Description.md` | Overview of system modules and functionality                       |

## Core Modules

* **Order Management:** Manage customer orders and order items
* **Menu Management:** Maintain menu items, prices, descriptions and categories
* **Table Management:** Track tables, reservations and table availability
* **Employee Management:** Store employee information, roles and operational details
* **Billing:** Maintain invoices and payment-related records
* **Customer Management:** Store customer information and feedback
* **Delivery Management:** Track delivery representatives and orders
* **Kitchen Operations:** Support order tracking and preparation workflows

## Database Design

The database uses a relational structure with interconnected entities for customers, employees, menu items, orders, tables, invoices and deliveries. **Primary and foreign keys** are used to maintain data integrity and establish relationships between operational modules.

## Setup

1. Install **MySQL** and **MySQL Workbench**.
2. Open `DDL.sql` in MySQL Workbench and execute it to create the database structure.
3. Execute `test_data.sql` to populate the database with sample records.
4. Use the resulting relational database to explore and query restaurant operations.

## Objective

The project demonstrates the application of **relational database design and SQL** to organize restaurant data and support efficient management of interconnected operational workflows.

