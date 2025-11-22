# ⚡ Grocery Store Sales Analysis Using SQL

*Analyzing customer behavior, product performance, sales trends, and supplier contribution using SQL.*

---

## 📌 Table of Contents

* <a href="#overview">Overview</a>
* <a href="#business-objective">Business Objective</a>
* <a href="#dataset">Dataset</a>
* <a href="#tools--technologies">Tools & Technologies</a>
* <a href="#project-structure">Project Structure</a>
* <a href="#data-preparation">Data Preparation</a>
* <a href="#analysis--sql-queries">Analysis & SQL Queries</a>
* <a href="#key-insights">Key Insights</a>
* <a href="#business-insights">Business Insights</a>
* <a href="#conclusion--learnings">Conclusion & Learnings</a>
* <a href="#experience--challenges">Experience & Challenges</a>
* <a href="#author--contact">Author & Contact</a>

---

<h2 id="overview">Overview</h2>

The **Grocery Store Sales Analysis** project explores how customers purchase products, which categories perform well, and which suppliers drive the most revenue.
Using **SQL**, this project converts raw transactional data into meaningful business insights that support better inventory management, revenue planning, and customer retention strategies.

---

<h2 id="business-objective">Business Objective</h2>

The key goals of this analysis are to:

* Understand **customer buying behavior** and repeat purchase patterns  
* Identify **top-performing product categories**  
* Highlight **high-value customers** based on total spend  
* Analyze **monthly sales trends** and seasonal peaks  
* Evaluate **supplier performance** and contribution to revenue  

---

<h2 id="dataset">Dataset</h2>

* **Dataset Name:** Grocery Store Sales Dataset  
* **Records:** 5,000+  
* **Tables Included:** Customers, Orders, Order Details, Products, Categories, Suppliers, Employees  
* **Data Type:** Transactional retail data  
* **Attributes:** Price, Quantity, Category, Customer, Supplier, Order Date, Revenue  

---

<h2 id="tools--technologies">Tools & Technologies</h2>

* **SQL (MySQL / PostgreSQL):** Data cleaning, joins, aggregation  
* **Excel / CSV:** Preprocessing & export  
* **VS Code / SQL Workbench:** Query execution  
* **Power BI (optional):** Visualization  

---

<h2 id="project-structure">Project Structure</h2>

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

<h2 id="data-preparation">Data Preparation</h2>

Key cleaning and transformation steps:

* Removed duplicate entries and incomplete records  
* Standardized category names, date formats, and numeric fields  
* Created calculated columns:  
  * `Total_Revenue = Quantity * Price`  
  * `Repeat_Customer_Flag`  
  * `Revenue_Per_Category`  
* Linked tables using **primary–foreign key relationships**  
* Ensured consistent mapping between customers, orders, suppliers, and products  

---

<h2 id="analysis--sql-queries">Analysis & SQL Queries</h2>

The analysis answers key business questions, including:

* Total number of unique vs. repeat customers  
* Product distribution across categories  
* Top 5 customers by purchase amount  
* Highest revenue-generating products  
* Monthly revenue and order count trends  
* Supplier contribution by total revenue  

---

<h2 id="key-insights">Key Insights</h2>

1. Of 200 total customers, **122 are repeat buyers**, showing strong loyalty.  
2. **Grains & Cereals** and **Snacks** categories have the highest number of products and highest demand.  
3. **Hand Sanitizer** is the top revenue-generating product.  
4. **January** shows the highest order volume and revenue.  
5. **Aarya** contributes the highest supplier-based sales revenue.  

---

<h2 id="business-insights">Business Insights</h2>

* Strong repeat customer rate indicates trust and customer satisfaction.  
* High sales in essential categories suggest focusing on **inventory optimization**.  
* High-value customers (like **Eshwar Iyer**) can be targeted for loyalty programs.  
* Festive months show a rise in sales → opportunity for targeted promotions.  
* Heavy reliance on a few suppliers signals supply chain risk → diversify suppliers.  

---

<h2 id="conclusion--learnings">Conclusion & Learnings</h2>

### 📊 Conclusion

This SQL-based analysis provides a deep understanding of grocery store sales performance.
Insights from customers, products, suppliers, and seasonal trends can help:

* Improve inventory planning  
* Increase customer retention  
* Optimize stock for high-demand categories  
* Boost revenue through data-driven decision-making  

### 🧠 Learnings

From this project, I learned to:

* Build advanced SQL queries using multiple joins  
* Analyze retail datasets effectively  
* Structure end-to-end data analysis projects  
* Derive insights from transactional data  

---

<h2 id="experience--challenges">Experience & Challenges</h2>

### 🧠 Experience

* Improved SQL proficiency through complex joins  
* Enhanced understanding of retail analytics  
* Developed ability to transform raw data into insights  

### 🚧 Challenges

* Cleaning inconsistent CSV files  
* Managing complex multi-table relationships  
* Optimizing heavy aggregation queries  

---

<h2 id="author--contact">Author & Contact</h2>

**Milind Bagad**  
📧 Email: (milindbagad7@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/milind-bagad-82786a224)  | 💻 [GitHub](https://github.com/milindbagad7)

---
