# 🍕 Pizza Sales Data Analysis Using SQL

## 📌 Project Overview

This project presents an end-to-end SQL data analysis performed on a pizza sales dataset.

The objective of this project was to analyze business performance using Structured Query Language (SQL) by extracting meaningful insights from multiple related tables.

The project covers:

- Database creation
- Data importing
- Relational joins
- Aggregations
- Trend analysis
- Advanced SQL techniques (Window Functions)

---

## 🗂 Dataset Description

The dataset consists of four relational tables:

### 1️⃣ Orders
Contains order ID, order date, and order time.

### 2️⃣ Order Details
Contains order line details and quantity of pizzas ordered.

### 3️⃣ Pizzas
Contains pizza size and price information.

### 4️⃣ Pizza Types
Contains pizza category, name, and ingredients.

All tables were imported and managed using MySQL inside MySQL Workbench.

---

## 🛠 Tools & Technologies Used

- SQL
- MySQL
- MySQL Workbench
- CSV Files

---

## 📊 Business Questions Solved

The following analytical questions were answered using SQL:

1. Retrieve the total number of orders placed.
2. Determine the distribution of orders by hour of the day.
3. Join relevant tables to find the category-wise distribution of pizzas.
4. Identify the most common pizza size ordered.
5. List the top 5 most ordered pizza types along with their quantities.
6. Join the necessary tables to find the total quantity of each pizza category ordered.
7. Calculate the total revenue generated from pizza sales.
8. Identify the highest-priced pizza.
9. Group the orders by date and calculate the average number of pizzas ordered per day.
10. Determine the top 3 most ordered pizza types based on revenue.
11. Calculate the percentage contribution of each pizza type to total revenue.
12. Analyze the cumulative revenue generated over time.
13. Determine the top 3 most ordered pizza types based on revenue for each pizza category.

---

## 🔍 SQL Concepts Applied

This project demonstrates the use of:

- SELECT statements
- WHERE conditions
- INNER JOIN
- GROUP BY
- ORDER BY
- Aggregate Functions (SUM, COUNT, AVG)
- Subqueries
- Date & Time Functions
- Window Functions (RANK())
- Cumulative Revenue Calculation

---

## 💡 Key Insights

- A small number of pizza types generated a large portion of total revenue.
- Evening hours showed peak ordering activity.
- Certain categories consistently outperformed others in total sales.
- Revenue trends highlighted specific high-performing days.

---

## 🏗 Database Setup Steps

1. Created a new database in MySQL.
2. Imported CSV files into respective tables.
3. Verified data types and relationships.
4. Established primary and foreign key relationships.
5. Executed analytical SQL queries to extract insights.

---

## 📁 Repository Structure

pizza-sales-sql-analysis/
│
├── dataset/
│   ├── orders.csv
│   ├── order_details.csv
│   ├── pizzas.csv
│   └── pizza_types.csv
│
├── sql_queries.sql
├── project_presentation.pdf
└── README.md

---

## 🚀 How to Run This Project

1. Clone this repository.
2. Open MySQL Workbench.
3. Create a new database.
4. Import the CSV files.
5. Run the `sql_queries.sql` file.

---

## 📈 Project Outcome

This project strengthened my understanding of:

- Relational database management
- Writing optimized SQL queries
- Performing business-focused data analysis
- Using advanced SQL features like window functions
- Extracting actionable insights from structured data

---

## 🔮 Future Improvements

- Add indexing for performance optimization
- Implement stored procedures
- Create a Power BI dashboard for visualization
- Extend analysis using more advanced SQL techniques

---
