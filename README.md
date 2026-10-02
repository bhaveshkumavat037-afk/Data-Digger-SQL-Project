# Data-Digger-SQL-Project
# Data Digger - SQL Database Project

## Overview
This repository contains the complete SQL database schema, queries, and project documentation for the **Data Digger** project. The project demonstrates core database concepts including relational database design, table creation, foreign key constraints, CRUD operations, and analytical query execution using MySQL/phpMyAdmin.

## Database Structure
The project consists of four interconnected tables:
- **Customers**: Stores customer details and contact information.
- **Orders**: Tracks order dates, customer IDs, and total purchase amounts.
- **Products**: Manages product inventory, pricing, and stock levels.
- **OrderDetails**: Links orders to products with item quantities and sub-totals.

## Repository Contents
- `datadigger.sql` - Full MySQL database dump (schema creation & data insertion).
- `Data_Digger_Project.pdf` - Project documentation report containing all executed SQL queries and phpMyAdmin output screenshots.

## How to Import
1. Open **XAMPP Control Panel** and start **Apache** and **MySQL**.
2. Go to **phpMyAdmin** (`http://localhost/phpmyadmin`).
3. Create a new database named `datadigger`.
4. Select `datadigger`, click on the **Import** tab, choose `datadigger.sql`, and click **Go**.
