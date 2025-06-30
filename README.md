# Task-4
eCommerce Sales Data Analysis using MySQL
Dataset: `ecommerce_big`

This project revolves around a mock eCommerce platform database that closely resembles platforms like Amazon, Flipkart, or Shopify. The database includes 4 core tables:

| Table Name     | Description                                      |
|----------------|--------------------------------------------------|
| `customers`    | Contains customer details like name and email    |
| `products`     | Product catalog with names, categories, and price|
| `orders`       | Transaction data including order dates and IDs   |
| `order_items`  | Line items of each order: quantity & product info|

 Technologies Used
- MySQL Workbench– SQL Querying and database creation  
- SQL (DDL + DML + Queries)– Data definition and data manipulation  
- Windows 11 – Local development environment

Objectives

The core aim of this project was to:
- Understand how relational databases work in an eCommerce context
- Perform data extraction, transformation, and analysis via SQL
- Gain practical experience with real-world business scenarios

Key Analytical Tasks

Each SQL file addresses a key eCommerce metric or analysis scenario, such as:
- Top-selling products
- Repeat customers
- Total revenue by date/category
- Average items per order
- Customer insights

These were done using advanced SQL techniques like:
- `JOINs`
- `GROUP BY`
- `HAVING`, `WHERE`
- Subqueries & Nested Selects
- Aggregate functions (`SUM`, `COUNT`, `AVG`)

Business Insights Extracted
A few real-world learnings simulated from this dataset:
1. High-value customers contribute to a large chunk of sales — supporting Pareto’s 80/20 rule.
2. Certain products consistently outperform in terms of both units sold and revenue — useful for inventory planning.
3. Order quantity patterns indicate bulk purchasing behavior during specific periods (e.g., festive seasons).

 Files in this Repo

| File Name              | Description                                     |
|------------------------|-------------------------------------------------|
| `task3_queries.sql`    | All SQL queries written during the analysis     |
| `README.md`            | Project overview and context                    |
| `screenshots/`         | MySQL Workbench screenshots for submission      |
