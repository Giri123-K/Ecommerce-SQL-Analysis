# 📊 E-Commerce Sales Analysis (Task 4) – SQL

## 📌 Introduction
This project is part of my Data Analyst Internship Task 4, where I analyzed Amazon e-commerce sales data using **MySQL**.  
The objective was to extract meaningful insights from the dataset using SQL queries, including filtering, grouping, joining, subqueries, and aggregations.

---

## 📂 Dataset
The dataset used is **Amazon Sale Report.csv**, containing e-commerce order details such as:
- `Order ID` – Unique identifier for each order  
- `Date` – Order date  
- `Status` – Order status (Shipped, Cancelled, Returned, etc.)  
- `Category` – Product category  
- `Qty` – Quantity ordered  
- `Amount` – Order amount in INR  
- `ship-city`, `ship-state`, `ship-country` – Shipping details  

---

## 🛠 Tools & Technologies
- **Database:** MySQL  
- **Data Source:** CSV file imported into MySQL  
- **Query Language:** SQL  
- **Platform:** MySQL Workbench  

---

## 🗂 SQL Queries Implemented
1. **Total revenue from shipped orders**
2. **Revenue by category**
3. **Average order value**
4. **Order count by status**
5. **Top 5 highest selling categories**
6. **Monthly revenue trend**
7. **Subquery example – Highest revenue category**
8. **Joins** – Linking sales table with a product details table
9. **View creation** – Saving frequent analysis queries as views

---

## 📷 Output Screenshots
*(Add screenshots of query outputs here)*  
Example:
- `total_revenue.png`
- `revenue_by_category.png`
- `monthly_trend.png`

---

## 🚀 How to Run the Project
1. Create a MySQL database:  
   ```sql
   CREATE DATABASE ecommerce;
   USE ecommerce;
   ```
2. Import the CSV into MySQL (using Data Import Wizard).
3. Run queries from `task4_queries.sql`.
4. View results in MySQL Workbench.

---

## 📎 Repository Structure
```
Ecommerce-SQL-Analysis/
│-- Amazon Sale Report.csv
│-- task4_queries.sql
│-- README.md
│-- screenshots/
```

---

## 📬 Author
**Girish K**  
*Data Analyst Intern*  
📧 girishgp123456@gmail.com  
🔗 https://www.linkedin.com/feed/
