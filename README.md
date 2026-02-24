# 🛍️ Customer Shopping Behavior Analysis
### An End-to-End Data Analytics Project | SQL · Python · Power BI

---

## 📌 Project Overview

This project simulates a **corporate-grade, end-to-end data analytics workflow** on retail customer shopping data. The goal is to extract actionable business intelligence from raw transactional data — covering the full pipeline from data cleaning and exploratory analysis, through SQL-based querying, to interactive dashboard reporting.

The analysis answers real business questions around **customer segmentation, revenue drivers, loyalty behavior, discount effectiveness, and product performance** — the kind of insights a Data Analyst would present to stakeholders or a Product team.

---

## 🗂️ Project Files

| File | Description |
|---|---|
| `customer_shopping_behavior.csv` | Raw dataset containing 3,900 customer transaction records |
| `Customer_Shopping_Behavior_Analysis.ipynb` | Python notebook — data cleaning, EDA, and SQL database loading |
| `customer_behavior_sql_queries.sql` | SQL scripts answering key business questions |
| `customer_behavior_dashboard.pbix` | Interactive Power BI dashboard |
| `Customer Shopping Behavior Analysis.pdf` | Final project report with findings and recommendations |
| `Customer-Shopping-Behavior-Analysis.pptx` | Stakeholder presentation deck |
| `Business Problem Document.pdf` | Business brief defining the problem scope and objectives |

---

## 🧰 Tech Stack

- **Python** (Pandas, NumPy, Matplotlib, Seaborn, SQLAlchemy) — Data wrangling & Exploratory Data Analysis (EDA)
- **SQL** (PostgreSQL) — Business query analysis and data aggregation
- **Power BI** — Interactive dashboard and data visualization
- **Jupyter Notebook** — Analysis environment

---

## 📊 Dataset

The dataset contains **3,900 rows** of retail customer transaction data with the following key features:

- **Demographics** — Age, Gender, Location
- **Transaction Details** — Item Purchased, Category, Purchase Amount (USD), Season
- **Customer Behavior** — Subscription Status, Frequency of Purchases, Previous Purchases
- **Purchase Attributes** — Shipping Type, Discount Applied, Promo Code Used, Payment Method, Review Rating

---

## 🔍 Key Business Questions Answered

The SQL analysis addresses the following business problems:

1. **Revenue by Gender** — What is the total revenue split between male and female customers?
2. **High-Value Discount Users** — Which customers used a discount but still spent above the average purchase amount?
3. **Top-Rated Products** — Which 5 products have the highest average review rating?
4. **Shipping Type vs. Spend** — Does shipping preference (Standard vs. Express) correlate with higher spending?
5. **Subscription Impact** — Do subscribed customers spend more? Comparing average spend and total revenue by subscription status.
6. **Discount Rate by Product** — Which products are most frequently purchased with a discount applied?
7. **Customer Segmentation** — Classifying customers into New, Returning, and Loyal segments based on purchase history using CTEs (Common Table Expressions).

---

## 🔄 Project Workflow

```
Raw CSV Data
     │
     ▼
Python (Jupyter Notebook)
 ├── Data Import & Inspection
 ├── Data Cleaning & Transformation
 ├── Exploratory Data Analysis (EDA)
 └── Load into SQL Database (via SQLAlchemy)
     │
     ▼
SQL (PostgreSQL)
 └── Business Question Queries & Aggregations
     │
     ▼
Power BI
 └── Interactive Dashboard & KPI Visualizations
     │
     ▼
Report & Presentation
 └── Business Insights & Recommendations
```

---

## ▶️ How to Run This Project

### Step 1 — Clone the repository
```bash
git clone https://github.com/hvp007/customer-trends-data-analysis-SQL-Python-PowerBI.git
cd customer-trends-data-analysis-SQL-Python-PowerBI
```

### Step 2 — Set up your Python environment
```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2 jupyter
```

### Step 3 — Run the Python Notebook
Open `Customer_Shopping_Behavior_Analysis.ipynb` in Jupyter Notebook and run all cells. This will:
- Load and clean the raw CSV data
- Perform exploratory data analysis
- Push the cleaned data into your local SQL database

### Step 4 — Run SQL Queries
- Open `customer_behavior_sql_queries.sql` in your SQL client (e.g. pgAdmin, DBeaver)
- Connect to the database created in Step 3
- Execute the queries to generate business insights

### Step 5 — Explore the Power BI Dashboard
- Open `customer_behavior_dashboard.pbix` in Power BI Desktop
- Connect to your local SQL database
- Explore the interactive KPI dashboard

---

## 💡 Key Insights & Business Recommendations

- **Loyal customers** (high previous purchase count) drive a disproportionate share of revenue — investing in a **retention strategy** such as loyalty rewards would protect this segment.
- **Subscribed customers** show significantly higher average spend, suggesting subscription-based promotions could be leveraged to convert non-subscribers.
- Several products show a **high discount rate** without a corresponding boost in review ratings — indicating that discounting may be unnecessary and margin could be recovered.
- **Express shipping users** tend to spend more per transaction, suggesting an opportunity to upsell premium shipping at checkout.

---

## 📄 License

MIT — free to use, fork, and adapt for your own portfolio.

---

## 👤 About

Built as a portfolio project to demonstrate end-to-end data analytics skills across the full stack: data engineering, SQL analysis, and business intelligence reporting.

*Feel free to ⭐ star this repository if you found it useful!*
