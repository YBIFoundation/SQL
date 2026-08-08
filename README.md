# SQL for Data Analytics

A practical SQL repository by **YBI Foundation** containing SQL queries, databases, datasets, and end-to-end analytics projects designed for learning and practicing **SQL for Data Analysis**.

This repository covers SQL fundamentals through advanced analytics concepts using real-world business scenarios such as **Marketing Analytics, Retail Sales, and Supply Chain Analytics**.

---

## 📚 What's Inside

| Project / Dataset                   | Description                                                                   |
| ----------------------------------- | ----------------------------------------------------------------------------- |
| **Digital Marketing Analytics**     | SQL queries for analyzing digital marketing performance                       |
| **Marketing Analytics**             | Marketing dataset and SQL database for analytics practice                     |
| **Marketing Joins**                 | Database designed for practicing SQL JOIN operations                          |
| **QueryMart – Retail Sales**        | Retail sales database with customers, products, orders, items, and warehouses |
| **Supply Chain Analytics**          | Supply chain dataset for business and operational analysis                    |
| **Supply Chain Advanced Analytics** | Advanced supply chain analytics dataset                                       |

---

# 🛒 QueryMart – Retail Sales Analytics

**QueryMart** is a retail business database designed for practicing SQL in a realistic business environment.

The project contains multiple related tables covering:

```text
Customers
Products
Orders
Items
Warehouses
```

### Database Files

* [QueryMart.db](QueryMart.db)
* [QueryMartCustomers.csv](QueryMartCustomers.csv)
* [QueryMartProducts.csv](QueryMartProducts.csv)
* [QueryMartOrders.csv](QueryMartOrders.csv)
* [QueryMartItems.csv](QueryMartItems.csv)
* [QueryMartWarehouses.csv](QueryMartWarehouses.csv)

### Example Business Questions

Using the QueryMart database, learners can answer questions such as:

* What is the total revenue?
* What are the top-selling products?
* Which customers generate the highest revenue?
* What is the average order value?
* Which warehouses generate the most revenue?
* What are the monthly sales trends?
* What are the most expensive orders?
* Which products have the highest sales?
* How does revenue vary by warehouse?
* What is the running total of revenue?
* What is the rank of each warehouse by revenue?

---

# 📣 Digital Marketing Analytics

The Digital Marketing Analytics project contains SQL queries for analyzing marketing performance.

### File

[DigitalMarketingAnalytics.sql](DigitalMarketingAnalytics.sql)

The project can be used to practice:

* Marketing campaign analysis
* Customer acquisition analysis
* Conversion analysis
* Revenue analysis
* Campaign performance
* Channel performance
* Aggregations
* Filtering
* Grouping
* Subqueries
* CASE statements
* Window functions

---

# 📊 Marketing Analytics

The Marketing Analytics database provides a structured dataset for practicing SQL-based business analysis.

### Files

* [MarketingAnalytics.db](MarketingAnalytics.db)
* [MarketingJoin.db](MarketingJoin.db)

### SQL Concepts

This project can be used to practice:

* `SELECT`
* `WHERE`
* `ORDER BY`
* `GROUP BY`
* `HAVING`
* Aggregate Functions
* `CASE`
* String Functions
* Date Functions
* Subqueries
* `JOIN`
* Window Functions
* Business KPIs

---

# 🔗 SQL JOIN Practice

`MarketingJoin.db` is designed specifically for understanding and practicing SQL joins.

Topics include:

```text
INNER JOIN
LEFT JOIN
RIGHT JOIN
FULL OUTER JOIN
SELF JOIN
CROSS JOIN
```

The database can be used to understand how multiple business tables are connected and how data can be combined for analysis.

---

# 🚚 Supply Chain Analytics

The repository also contains supply chain datasets for analyzing operational and business performance.

### Supply Chain Analytics

* [SupplyChainAnalytics.csv](SupplyChainAnalytics.csv)
* [SupplyChainAnalytics.db](SupplyChainAnalytics.db)

### Advanced Supply Chain Analytics

* [SupplyChainAdvanceAnalytics.csv](SupplyChainAdvanceAnalytics.csv)
* [SupplyChainAdvanceAnalytics.db](SupplyChainAdvanceAnalytics.db)

These datasets can be used to practice analysis around:

* Inventory
* Orders
* Suppliers
* Products
* Warehouses
* Logistics
* Delivery performance
* Supply chain efficiency
* Operational KPIs
* Business performance

---

# 🧠 SQL Learning Roadmap

This repository can be followed progressively:

### Level 1 – SQL Fundamentals

```text
SELECT
WHERE
DISTINCT
ORDER BY
LIMIT
Aliases
```

### Level 2 – SQL Functions

```text
Aggregate Functions
String Functions
Date Functions
Mathematical Functions
CASE Statements
```

### Level 3 – Data Aggregation

```text
GROUP BY
HAVING
COUNT
SUM
AVG
MIN
MAX
```

### Level 4 – SQL JOINs

```text
INNER JOIN
LEFT JOIN
RIGHT JOIN
FULL OUTER JOIN
SELF JOIN
CROSS JOIN
```

### Level 5 – Advanced SQL

```text
Subqueries
CTEs
Window Functions
RANK()
DENSE_RANK()
ROW_NUMBER()
LAG()
LEAD()
Running Totals
```

### Level 6 – Business Analytics

```text
Revenue Analysis
Customer Analysis
Product Analysis
Marketing Analytics
Supply Chain Analytics
Sales Analytics
Performance Analysis
KPI Analysis
```

---

# 💻 Working With the Databases

The `.db` files are **SQLite databases** and can be opened using:

* Python
* Jupyter Notebook
* Google Colab
* SQLite
* DB Browser for SQLite
* VS Code with SQLite extensions

### Example: Using SQLite with Python

```python
import sqlite3
import pandas as pd

conn = sqlite3.connect("QueryMart.db")

query = """
SELECT *
FROM Customers
LIMIT 10;
"""

df = pd.read_sql_query(query, conn)

df
```

---

# 🐍 SQL + Python

These databases can also be used with Python for complete data analytics workflows:

```text
SQLite Database
       ↓
     SQL
       ↓
Data Extraction
       ↓
    Pandas
       ↓
Data Analysis
       ↓
Visualization
       ↓
Business Insights
```

This makes the repository useful for learners building skills in both **SQL and Python Data Analytics**.

---

# 🎯 Learning Objectives

After working through these projects, learners should be able to:

* Write SQL queries confidently
* Filter and transform data
* Aggregate business data
* Combine multiple tables using JOINs
* Work with dates and strings
* Use conditional logic with `CASE`
* Write subqueries and CTEs
* Use window functions
* Calculate business KPIs
* Analyze sales and marketing data
* Perform customer and product analysis
* Analyze supply chain performance
* Solve real-world business questions using SQL

---

# 🏆 Recommended Practice Workflow

For each dataset, follow this workflow:

```text
1. Understand the Business Problem
            ↓
2. Explore the Tables
            ↓
3. Identify Required Columns
            ↓
4. Write SQL Query
            ↓
5. Validate the Result
            ↓
6. Extract Business Insight
            ↓
7. Build Dashboard / Visualization
```

---

# 📁 Repository Structure

```text
SQL/
│
├── DigitalMarketingAnalytics.sql
│
├── MarketingAnalytics.db
├── MarketingJoin.db
│
├── QueryMart.db
├── QueryMartCustomers.csv
├── QueryMartItems.csv
├── QueryMartOrders.csv
├── QueryMartProducts.csv
├── QueryMartWarehouses.csv
│
├── SupplyChainAnalytics.csv
├── SupplyChainAnalytics.db
│
├── SupplyChainAdvanceAnalytics.csv
├── SupplyChainAdvanceAnalytics.db
│
└── README.md
```

---

# 👨‍💻 Who Is This Repository For?

This repository is suitable for:

* SQL Beginners
* Data Analyst Students
* Business Analytics Students
* College Students
* SQL Interview Preparation
* Data Analytics Portfolio Projects
* Python + SQL Learners
* Aspiring Data Analysts
* Professionals refreshing their SQL skills

---

# 🚀 How to Use This Repository

### Step 1 – Clone the Repository

```bash
git clone https://github.com/YBIFoundation/SQL.git
```

### Step 2 – Open the Database

Choose any `.db` file and open it using SQLite, Python, Jupyter Notebook, Google Colab, or DB Browser for SQLite.

### Step 3 – Explore the Tables

Understand the structure, columns, relationships, and available data.

### Step 4 – Solve Business Problems

Write SQL queries to answer analytical questions.

### Step 5 – Build Your Portfolio

Use the datasets to create:

* SQL projects
* Data analysis reports
* Power BI dashboards
* Python analytics projects
* GitHub portfolio projects

---

# 📌 Projects Included

| Project                         | Format         | Focus              |
| ------------------------------- | -------------- | ------------------ |
| Digital Marketing Analytics     | `.sql`         | Marketing          |
| Marketing Analytics             | `.db`          | Business Analytics |
| Marketing Join Practice         | `.db`          | SQL JOINs          |
| QueryMart Retail Analytics      | `.db` + `.csv` | Retail Sales       |
| Supply Chain Analytics          | `.db` + `.csv` | Supply Chain       |
| Supply Chain Advanced Analytics | `.db` + `.csv` | Advanced Analytics |

---

# ⭐ Support the Repository

If you find this repository useful for learning SQL:

**⭐ Star this repository**

**🍴 Fork the repository**

**📢 Share it with other learners**

**💻 Build your own project using the datasets**

---

# 🌐 YBI Foundation

This repository is part of the practical learning resources developed by **YBI Foundation** for students and aspiring data professionals.

Learn. Practice. Build. Deploy.

**YBI Foundation**

---

## 📜 License

This repository is intended for **educational and learning purposes**.

Please refer to the repository and individual dataset files for any applicable usage restrictions.
