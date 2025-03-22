# pizza_sales----SQL
🍕 Pizza Sales Analysis using SQL
📌 Problem Statement
Built an ETL pipeline to extract, transform, and load Pizza company sales data into a structured database. Using SQL queries, we analyzed consumer behavior, sales trends, and operational performance to derive meaningful insights that help in data-driven decision-making for the pizza business.

📊 Dataset Overview
The dataset consists of four tables containing order details, pizza types, and sales information.

1️⃣ Order Details
Stores detailed information about each pizza sold in an order.
order_details_id (Primary Key)
order_id (Foreign Key → orders)
pizza_id (Foreign Key → pizzas)
quantity (Number of pizzas ordered)

2️⃣ Orders
Contains timestamps of customer orders.
order_id (Primary Key)
order_date (Date of order)
order_time (Time of order)

3️⃣ Pizza Types
Defines pizza flavors and their categories.
pizza_type_id (Primary Key)
name (Pizza name, e.g., "Hawaiian")
category (Pizza category, e.g., "Vegetarian", "Classic")
ingredients (List of ingredients)

4️⃣ Pizzas
Describes pizza sizes and pricing.
pizza_id (Primary Key)
pizza_type_id (Foreign Key → pizza_types)
size (Small, Medium, Large)
price (Cost of the pizza)

⚙️ Technology Stack
ETL Pipeline: Extract, Transform (Excel), Load into SQL
SQL: Data transformation & analysis
Excel: Initial data cleaning & formatting
Database Management: Structured storage of pizza sales data.

🏗 Methodology
1️⃣ Format Data: Cleaned and structured raw pizza sales data using Excel.
2️⃣ Load into SQL: Imported structured data into a MySQL database.
3️⃣ Data Transformation: Established relationships between tables using keys (e.g., Orders → Order Details → Pizzas → Pizza Types).
4️⃣ SQL Querying & Analysis:

Used aggregations, joins, and conditional computations to derive insights.
📈 SQL Querying & Data Analysis
🔹 Key SQL Operations Used
✅ Aggregation (SUM, COUNT, AVG) → For revenue & order analysis.
✅ Joins (INNER JOIN, LEFT JOIN) → To connect customer orders, pizzas, and their details.
✅ Conditional Columns (CASE WHEN) → To classify pizza categories and transactions.
✅ Filtering (WHERE, HAVING) → To extract relevant insights.
✅ Grouping & Sorting (GROUP BY, ORDER BY) → To rank sales trends.

Insights & Business Impact
✅ Identify best-selling pizzas & categories 🍕
✅ Determine peak sales hours & days ⏳
✅ Analyze order frequency & customer demand 📈
✅ Optimize pricing 📊💰
✅ Improve store operations & marketing strategies 📊

This structured SQL analysis helps Pizza company enhance sales strategies and boost customer satisfaction! 🚀



