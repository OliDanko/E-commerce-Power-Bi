# 🛒 E-commerce Sales Database Project

This project simulates a **relational database for an e-commerce sales system** and demonstrates ** SQL skills** and **business analytics** in action.

---

# Project Overview

The goal of this project is to **analyze sales data** from an online store using SQL.  
It covers:

- Table creation with proper **relationships** (Star Schema)
- Sample data simulating realistic **customers, products, and orders**
- Analytical queries answering real **business questions**

The database includes **three main entities**:

- **Customers** – personal and regional information about buyers  
- **Products** – product catalog including categories and pricing  
- **Orders** – sales transactions with date, quantity, and total amount  

---

# Technologies Used

- **SQL (MySQL syntax)**  
- Local SQL environment (MySQL Workbench)  
- Data modeling  (Customers ↔ Orders ↔ Products)  

---

# Database Schema

| Table     | Description |
|-----------|-------------|
| **Customers** | Customer names, region, and contact details |
| **Products**  | Product name, category, and price |
| **Orders**    | Order transactions including product, customer, quantity, and total amount |

Tables are connected via **primary keys** and **foreign keys**:  

- `Orders.CustomerID → Customers.CustomerID`  
- `Orders.ProductID → Products.ProductID`  

---

# Sample Insights & Query Highlights

This project includes SQL queries that answer **real business questions**:

✅ **Basic queries**  
- Total number of products  
- Average product price  
- Most expensive products  

✅ **Intermediate analytics**  
- Total revenue by region  
- Top-selling categories  
- Monthly sales trends  

✅ **Advanced analytics**  
- Ranking products by revenue in each category  
- Calculating revenue share per region (%)  
- Identifying top 10 VIP customers  

---

# Techniques Used

- `SELECT`, `JOIN`, `GROUP BY`, `ORDER BY`  
- Aggregation (`SUM`, `AVG`, `COUNT`, etc.)  
- Window functions (`RANK`, `LAG`)  
- Date formatting (`DATE_FORMAT`)  
- Percent calculations  


