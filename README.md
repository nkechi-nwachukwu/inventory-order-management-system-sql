# 📦 Inventory Order Management Database System

# 📌 Project Overview
This project is a relational database system that simulates real-world supply chain and inventory operations, managing suppliers, products, warehouses, orders, and shipments.
It also represents a core ERP module, showcasing how supply chain processes are integrated within a centralized system for efficient operations and decision-making.

---

## 🎯 Objective
To solve common supply chain problems such as:
- Stock shortages
- Overstocking
- Poor supplier tracking
- Inefficient order fulfillment
---

## 🧱 Database Structure
The database consists of the following tables:
- Suppliers
- Products
- Warehouses
- Inventory
- PurchaseOrders
- PurchaseOrderItems
- SalesOrders
- SalesOrderItems
- Shipments
---

## 🛠 Tools Used
- SQL (MySQL)
- MySQL Workbench
- Database Design (EER Diagram)
---

## 🗂 Project Structure
Supply-Chain-DBMS/
│
├── README.md
│   └── Project overview, features, and documentation
│
├── database/
│   ├── schema.sql
│   │   └── Database structure (CREATE DATABASE + TABLES)
│   │
│   ├── data.sql
│       └── Sample data inserts for testing
│
├── queries/
│   ├── analysis.sql
│       └── SQL queries for business insights and reporting
│
├── diagrams/
│   ├── erd.png
│       └── Entity Relationship Diagram showing database structure
│
├── screenshots/
│   ├── top_selling_products.png
│   ├── revenue_by_category.png
│   ├── low_stock.png
│   ├── supplier_performance.png
│   ├── monthly_revenue.png
│    └── Query outputs and results visualized from SQL analysis

---
## 📊 Key SQL Analysis
🔹 Top Selling Products
Identifies best-performing products based on total quantity sold.
🔹 Revenue by Category
Analyzes total revenue generated across different product categories.
🔹 Stock Shortage Detection
Detects products with low inventory levels to prevent stockouts.
🔹 Supplier Performance Ranking
Evaluates supplier efficiency based on supply volume and order frequency.
🔹 Monthly Revenue Trends
Tracks revenue performance over time to identify growth patterns.
🔹 Delivery Performance
Measures delivery success rate and overall fulfillment efficiency.
🔹 Low Stock Alerts
Flags items that require urgent restocking.

---
## 🖼 ERD Diagram 
![ERD Diagram](diagrams/erd.png) 

---
## 📸 Sample Query Outputs
 Top Selling Products ![Top Selling Products] 
 Revenue by Category ![Revenue by Category] 
 Low Stock Alert ![Low Stock]

---
