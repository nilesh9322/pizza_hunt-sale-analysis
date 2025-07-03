# 🍕 Pizza Sales Analysis Using SQL

## 📌 Project Overview
This project provides a comprehensive analysis of pizza sales data using SQL. The goal is to uncover key business insights such as revenue trends, top-selling items, and customer ordering behavior. The dataset includes information on orders, order details, pizza types, and prices.

---

## 🗃️ Dataset Tables
- **orders**: Contains order ID, date, and time.
- **order_details**: Maps orders to pizzas and quantities.
- **pizzas**: Contains pizza IDs, types, prices, and sizes.
- **pizza_types**: Describes pizza names, categories, and types.

---

## 🔍 Key SQL Insights

### 🧾 Sales & Revenue
- **Total Revenue**: Calculated using the quantity ordered and price per pizza.
- **Highest Priced Pizza**: Identified by sorting pizzas by price in descending order.
- **Top 3 Pizzas by Revenue**:
  - Ranked pizzas by total revenue generated.
  - Useful for optimizing the menu and promotions.
- **Revenue Contribution by Category**:
  - Calculated each category's percentage share of total revenue.

### 📦 Orders & Products
- **Top 5 Most Ordered Pizzas**:
  - Aggregated by quantity ordered.
- **Most Common Pizza Size**:
  - Determined which size (S, M, L, etc.) was most frequently sold.
- **Category-Wise Orders**:
  - Summed up total orders per pizza category.

### 🕒 Customer Behavior
- **Orders by Hour**:
  - Shows peak hours of pizza ordering, useful for staffing and delivery planning.
- **Average Pizzas Ordered per Day**:
  - Helps in understanding daily order volume.
- **Cumulative Revenue Over Time**:
  - Tracks revenue growth to monitor business performance.

---

## 🛠️ SQL Concepts Used
- JOINs (INNER JOIN)
- Aggregate functions: `SUM()`, `COUNT()`, `AVG()`, `ROUND()`
- Window functions: `RANK() OVER(PARTITION BY ...)`
- Subqueries and CTEs
- GROUP BY and ORDER BY

---

## 📈 Business Impact
- Optimized product offering by identifying top revenue generators.
- Improved resource planning by analyzing customer order patterns.
- Supported data-driven marketing strategies based on category performance.

---

## 📂 File Structure
📦 pizza-sales-analysis
┣ 📄 pizzas_hunt.sql
┣ 📄 README.md


---

## 📬 Contact
nilesh bhondage
📧 nileshbhondge@gmail.com  
📱 9322942266 

---
