📄 Overview
This project demonstrates a complete SQL-based business analysis workflow for a sales and inventory system. It covers database creation, table design, data relationships, and analytical queries to extract insights on customers, products, sales, suppliers, and employee performance.

🗄 Database Structure
The database consists of 7 tables:

supplier – Supplier details

categories – Product categories

employees – Employee details

customers – Customer details

products – Product list with supplier & category mapping

orders – Order records with customer & employee mapping

order_details – Item-level sales information

📊 Key Analysis Performed
1️⃣ Customer Insights
Unique customers count

Top customers by orders & purchase amount

Average and total spend per customer

2️⃣ Product Performance
Products per category

Average price by category

Best-selling products (quantity & revenue)

Sales by category and supplier

3️⃣ Sales & Order Trends
Total orders & average order value

Most active order dates

Monthly order & revenue trends

Weekday vs weekend sales comparison

4️⃣ Supplier Contribution
Supplier count & product contribution

Average product price per supplier

Revenue generated per supplier

5️⃣ Employee Performance
Number of employees handling orders

Orders processed per employee

Total & average sales value per employee

6️⃣ Order Details Deep Dive
Quantity vs total price relationship

Average quantity per product

Unit price variation across orders

🛠 Technologies Used
MySQL – Database creation, joins, aggregation, and date functions

SQL Queries – Complex joins, group by, order by, aggregate functions, and constraints

📂 Repository Structure
pgsql
Copy
Edit
📁 SQL_Project
 ├── SQL_Project.sql   # Full SQL script with schema + analysis queries
 └── README.md         # Project documentation
