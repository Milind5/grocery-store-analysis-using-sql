# 📊 Grocery Store Sales Analysis Using SQL

_Analyzing customer behavior, product performance, sales trends, and supplier contribution using SQL._

---

## 📌 Table of Contents  
- [Overview](#overview)  
- [Business Objective](#business-objective)  
- [Dataset](#dataset)  
- [Tools & Technologies](#tools--technologies)  
- [Project Structure](#project-structure)  
- [Data Preparation](#data-preparation)  
- [Analysis & SQL Queries](#analysis--sql-queries)  
- [Key Insights](#key-insights)  
- [Business Insights](#business-insights)  
- [Conclusion & Learnings](#conclusion--learnings)  
- [Experience & Challenges](#experience--challenges)  
- [Author & Contact](#author--contact)

---

## 📘 Overview
The **Grocery Store Sales Analysis** project explores how customers purchase groceries, which products perform well, and which suppliers drive revenue.  
Using **SQL**, this project answers key business questions and transforms raw sales data into meaningful insights that help improve inventory planning, customer satisfaction, and sales growth.

---

## 🎯 Business Objective
The main goals of this project are to:

- Analyze **customer purchase behavior** and repeat buying trends  
- Identify **high-performing product categories**  
- Find **top buyers** contributing most to store revenue  
- Understand **monthly sales and seasonal patterns**  
- Evaluate **supplier contribution** toward overall revenue  

---

## 📂 Dataset
- **Dataset Name:** Grocery Store Sales Dataset  
- **Records:** 5,000+  
- **Tables Included:** Customers, Orders, Products, Categories, Suppliers, Order Details, Employees  
- **Duration:** 1-year transaction data  
- **Attributes:** Product Category, Price, Order Quantity, Customer, Supplier, Order Date, Revenue  

---

## 🛠 Tools & Technologies
- **SQL (MySQL / PostgreSQL)** – Data analysis, joins, aggregation  
- **Excel / CSV** – Data formatting & preprocessing  
- **Power BI / Tableau (optional)** – Visualization  
- **VS Code / SQL Workbench** – Query execution  

---

## 📁 Project Structure

```
grocery-store-analysis/
│
├── README.md
│
├── data/
│   ├── Customers.csv
│   ├── Orders.csv
│   ├── OrderDetails.csv
│   ├── Products.csv
│   ├── Categories.csv
│   ├── Suppliers.csv
│   └── Employees.csv
│
├── sql_queries/
│   ├── unique_customers.sql
│   ├── products_by_category.sql
│   ├── top_customers.sql
│   ├── revenue_by_product.sql
│   ├── monthly_sales.sql
│   ├── supplier_revenue.sql
│
└── images/
    └── dashboard.png
```

---

## 🧹 Data Preparation
Performed detailed data cleaning and transformation:

- Removed duplicates and missing records  
- Standardized text, categories, and date formats  
- Created calculated columns:
  - `Total_Revenue = Quantity * Price`  
  - `Repeat_Customer_Flag`  
  - `Revenue_Per_Category`  

- Connected tables using:
  - CustomerID  
  - ProductID  
  - SupplierID  
  - OrderID  

---

## 🧮 Analysis & SQL Queries
The project answers key questions:

- Total **unique & repeat customers**  
- Product count by **category**  
- **Top 5 customers** by revenue  
- **Highest revenue-generating** products  
- **Monthly** order and revenue trends  
- **Supplier contribution** to total revenue  

---

## 📊 Key Insights
1. Out of **200 customers**, **122 are repeat buyers**, showing high loyalty.  
2. **Grains & Cereals** and **Snacks** are the most in-demand categories.  
3. **Hand Sanitizer** generates the highest revenue.  
4. **January** has the highest sales and orders.  
5. **Aarya** is the top supplier contributing major revenue.

---

## 💡 Business Insights
- High customer retention → strong store trust.  
- Essential items like **Grains & Snacks** drive most sales.  
- Loyalty programs can target high-value buyers like **Eshwar Iyer**.  
- Sales spike during **festive months**, opening promo opportunities.  
- Heavy dependency on few suppliers → diversify to reduce risk.

---

## 📌 Conclusion & Learnings

### ✔ Conclusion  
This project provides a complete view of grocery store performance.  
It enables better decision-making in:

- Stock optimization  
- Customer behavior analysis  
- Revenue growth planning  
- Supplier management  

### ✔ Learnings  
- Performed end-to-end SQL data analysis  
- Learned multi-table joins & analytical query writing  
- Gained insights into retail industry dynamics  
- Improved skills in structuring data projects

---

## ⚠ Experience & Challenges

### 🧠 Experience  
- Wrote complex SQL join queries  
- Improved analytical reasoning  
- Converted raw data into actionable insights  

### 🚧 Challenges  
- Cleaning data across multiple CSVs  
- Managing multi-table joins  
- Optimizing complex aggregate queries  

---

## 👤 Author & Contact

**Milind Bagad**  
📧 Email: (milindbagad7@gmail.com) 
🔗 LinkedIn: (https://www.linkedin.com/in/milind-bagad-82786a224)
💻 GitHub: (https://github.com/Milind5)
