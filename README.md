# Advanced E-Commerce Database System with Analytics (MySQL)

## 📌 Project Overview
This project is a fully designed and implemented **E-Commerce Database System** using MySQL. It simulates a real-world online shopping platform and demonstrates advanced SQL techniques for data management and business analysis.

---

##  Database Design
The database consists of the following tables:

- Customers
- Categories
- Products
- Orders
- Order_Items
- Payments

### Relationships:
- One customer can place multiple orders
- Each order contains multiple products
- Products belong to categories

---

## Features Implemented

### Core SQL
- JOINs (multi-table queries)
- GROUP BY & HAVING
- Subqueries

### Advanced SQL
- Window Functions (RANK)
- Common Table Expressions (CTE)
- Views for analytics

###  Database Features
- Stored Procedures
- Triggers (auto-update stock)
- Indexing (query optimization)

---

## Key Queries

- Top customers by total spending
- Most sold products
- Monthly revenue trends
- Customers with multiple orders
- Products never ordered

---

## 📈 Business Insights

- Top customers contribute a significant portion of total revenue
- Some products have no sales, indicating potential inventory issues
- Repeat customers generate higher revenue than one-time buyers
- Sales show variation across different time periods

---

## Project Structure

Ecommerce-SQL-Project/
├── ecommerce_project.sql
├── ER_diagram.png
├── README.md


---

##  Tools Used

- MySQL Workbench
- SQL

---

## 🚀 How to Run

1. Open MySQL Workbench  
2. Import `ecommerce_project.sql`  
3. Execute the script  
4. Run queries to analyze data  

---

## ER Diagram
<img width="797" height="642" alt="E-commerce EER Diagram" src="https://github.com/user-attachments/assets/534acb52-155f-4247-a4aa-4c35d3cf1898" />


## Author
Phoo Pyae Thaw
