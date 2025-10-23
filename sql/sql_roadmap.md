# SQL Basics & Foundations

**Topics:**

* What is SQL? Importance for data analysts
* Understanding databases, tables, schemas
* Data types: `INT`, `VARCHAR`, `DATE`, `BOOLEAN`
* `SELECT` statements
* `WHERE` clause for filtering
* `ORDER BY`, `LIMIT`
* `DISTINCT`, `BETWEEN`, `IN`, `LIKE`
* Arithmetic and string operations

**Practice Ideas:**

* Use PostgreSQL or MySQL
* Query a small sample dataset (Employees, Sales, or Customers)
* Filter, sort, and extract insights

---

# Intermediate SQL (Data Manipulation)

**Topics:**

* **Joins:** `INNER`, `LEFT`, `RIGHT`, `FULL`
* Understanding primary and foreign keys
* **Aggregations:** `GROUP BY`, `HAVING`
* **Aggregate functions:** `SUM`, `COUNT`, `AVG`, `MIN`, `MAX`
* **Subqueries:** in `WHERE`, `FROM`, `SELECT`
* **CASE WHEN** for conditional logic
* **Aliases** with `AS`
* Handling `NULL` values

**Practice Ideas:**

* Combine `orders`, `customers`, and `products` tables
* Find top-selling products by region
* Compute monthly revenue and growth

---

# Advanced SQL (Analytical Level)

**Topics:**

### Window Functions

* `ROW_NUMBER()`, `RANK()`, `DENSE_RANK()`
* `LAG()`, `LEAD()`
* `SUM() OVER(PARTITION BY …)`
* Running totals, moving averages

### Common Table Expressions (CTEs)

* Using the `WITH` clause
* Recursive CTEs

### Set Operations

* `UNION`, `INTERSECT`, `EXCEPT`

### Data Cleaning & Transformation

* `TRIM()`, `UPPER()`, `LOWER()`, `REPLACE()`
* Handling missing or invalid data
* Date functions: `EXTRACT()`, `DATE_TRUNC()`, `DATEDIFF()`

### Analytical Use Cases

* Percent of total calculations
* Cohort and churn analysis
* Customer segmentation
* Time-series and trend analysis

---

# Database Design & Performance

**Topics:**

* Normalization: 1NF, 2NF, 3NF
* Primary Keys vs Foreign Keys
* Indexing and query optimization (`EXPLAIN`)
* Creating and using **Views** and **Materialized Views**
* Basic user permissions and database security

---

 # Business Analytics with SQL

**Topics:**

* Identify revenue drivers (Pareto / 80-20 analysis)
* Monthly active user trends
* Marketing channel performance
* Repeat customer behavior
* Customer retention & churn metrics
* Product category analysis

**Datasets for Practice:**

* Kaggle: E-commerce, Spotify, Airbnb datasets
* Mode Analytics SQL practice
* LeetCode SQL (Medium–Hard level)

---

# SQL Integration with Tools

**Topics:**

* Using SQL with **Excel** or **Google Sheets**
* Connecting SQL to **Power BI** or **Tableau**
* Fetching SQL results into **Python (pandas.read_sql)**

---

# Final Hiring Project — Data-Driven Business Insights Dashboard

**Project Title:**
**“Analyzing E-Commerce Performance using SQL and Power BI”**

**Objective:**
Help a fictional company (*ShopMax*) uncover insights on **sales trends, customer retention, and product performance.**

**Dataset:**
Use Kaggle’s [E-Commerce Data (UK Online Retail)](https://www.kaggle.com/datasets/carrie1/ecommerce-data)

**Tables:**

* `customers`
* `orders`
* `order_items`
* `products`

**SQL Tasks:**

1. **Customer Analysis**

   * New vs returning customers by month
   * Top 10 customers by lifetime spend
   * Retention rate by cohort

2. **Sales Analysis**

   * Monthly revenue, AOV, and profit margin
   * Top-performing categories
   * Seasonal sales trends

3. **Product Insights**

   * Top 5 products by profit and quantity
   * Products with declining sales
   * Average revenue by category

4. **Business Health Metrics**

   * Monthly growth rate (%)
   * Repeat purchase rate
   * Customer lifetime value (CLV)

**Deliverables:**

* Clean SQL scripts (with documentation)
* Power BI / Tableau dashboard
* One-page business insights summary

**Recruiter Hook:**

> “Built a SQL-powered business insights dashboard analyzing 100K+ transactions to identify sales drivers, retention trends, and growth opportunities for an e-commerce brand.”

---

 # 6-Week Learning Timeline (4 Hours per Day)

| Week | Focus Area                     | Outcome                             |
| ---- | ------------------------------ | ----------------------------------- |
| 1    | SQL Basics                     | Write basic queries confidently     |
| 2    | Joins & Aggregations           | Perform multi-table analysis        |
| 3–4  | Advanced SQL                   | Handle analytics & window functions |
| 5    | Database Design & Optimization | Write efficient queries             |
| 6    | Capstone Project               | Build a hiring-ready dashboard      |

---

## # Recommended Resources

**Practice & Learning:**

* [LeetCode SQL Problems](https://leetcode.com/problemset/database/)
* [Mode Analytics SQL Tutorial](https://mode.com/sql-tutorial/)
* [Kaggle Datasets](https://www.kaggle.com/datasets)

**YouTube Channels:**

* *Data with Danny*
* *Luke Barousse*

**Book:**

* *SQL for Data Analytics (O’Reilly)*
