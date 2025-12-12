# Grocery_Store_Management
"GROCEREASE" named project on grocery store management using MY SQL Workbench

This project simulates a real-world grocery store management system using SQL. It focuses on designing a relational database that tracks and analyzes store operations involving customers, products, suppliers, employees, and orders.

With well-structured SQL queries and insights, the project enables data-driven decisions for inventory management, customer behavior analysis, supplier evaluation, and employee performance monitoring.

## Key Features

- **Normalized Database Schema**: Eight interconnected tables (Suppliers, Categories, Products, Customers, Store_Employees, Orders, OrderDetails) with primary/foreign keys, cascading updates/deletes for data integrity.
- **Realistic Sample Data**: 200+ customers across Indian cities, 50 diverse grocery products (rice, spices, dairy, household items) priced realistically, 300+ order records with detailed line items showing quantities and totals.
- **Business Intelligence Queries**: 25+ analytical SQL queries across categories like customer insights (top spenders, order frequency), product performance (category-wise sales, revenue leaders), sales trends (monthly volumes, peak dates), supplier/employee contributions.

## Core Analyses Performed

| Analysis Category | Key Insights Generated |
|-------------------|-----------------------|
| Customer Insights | Unique customers, top 5 by spend, average purchase value |
| Product Performance | Products per category, avg prices, highest sales volume, revenue by supplier/category |
| Sales Trends | Total orders, avg order value, peak dates, monthly revenue trends |
| Supplier/Employee | Top suppliers by products/revenue, employees by orders/sales value |
| Order Deep Dive | Quantity-price relationships, avg quantities per product |

## Technologies & Setup

Built with MySQL-compatible SQL. Run `Grocery-Store-Management.sql` to create database, import CSV data (Orders.csv, OrderDetails.csv, etc.), and execute analyses. Includes helper procedures like `alltablesdata()` for quick data validation.

Perfect for Data Science portfolios, demonstrating schema design, complex JOINs, aggregations (COUNT, SUM, AVG, GROUP BY), and real-world retail analytics. 


# Author
Ruchita Patil Email: pruchita565@gmail.com

LinkedIn Profile: www.linkedin.com/in/patil-ruchita
