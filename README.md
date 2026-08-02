# 🛍️ Retail Sales Analysis | SQL Data Analytics Project
A beginner-friendly SQL portfolio project that analyzes retail sales data using PostgreSQL to generate meaningful business insights.

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-025E8C?style=for-the-badge)
![pgAdmin](https://img.shields.io/badge/pgAdmin-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

## 📖 Project Overview

This project demonstrates the use of PostgreSQL to analyze retail sales data and generate meaningful business insights. It covers the complete SQL data analysis workflow, including database creation, data cleaning, exploratory data analysis (EDA), and solving business-oriented analytical problems using SQL queries. This project is part of my Data Analytics portfolio and showcases practical SQL skills used in real-world data analysis.

---

## 🎯 Objectives

- Create a retail sales database using PostgreSQL.
- Import and organize retail sales data.
- Clean and validate the dataset.
- Perform Exploratory Data Analysis (EDA).
- Solve business problems using SQL queries.
- Generate actionable business insights.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| PostgreSQL | Database |
| pgAdmin 4 | Database Management |
| SQL | Data Analysis |
| Git | Version Control |
| GitHub | Project Hosting |

---

## 📁 Dataset

The dataset contains retail sales transactions with the following attributes:

- Transaction ID
- Sale Date
- Sale Time
- Customer ID
- Gender
- Age
- Product Category
- Quantity
- Price Per Unit
- Cost of Goods Sold (COGS)
- Total Sale

---

## 📂 Project Structure

```text
Retail-Sales-Analysis/
│
├── README.md
├── dataset/
│   └── SQL-Retail Sales Analysis_utf.csv
│
└── sql_project1.sql

```
---

## 📄 Repository Contents

| File | Description |
|------|-------------|
| README.md | Project documentation |
| sql_project1.sql | Database creation and SQL analysis queries |
| dataset/SQL-Retail Sales Analysis_utf.csv | Retail sales dataset |

---

## 🗄️ Database Schema

### Database Creation

```sql
CREATE DATABASE p1_retail_db;
```

### Table Creation

```sql
CREATE TABLE retail_sales
(
    transactions_id INT PRIMARY KEY,
    sale_date DATE,
    sale_time TIME,
    customer_id INT,
    gender VARCHAR(10),
    age INT,
    category VARCHAR(35),
    quantity INT,
    price_per_unit FLOAT,
    cogs FLOAT,
    total_sale FLOAT
);
```

---

## 🧹 Data Cleaning

The following data cleaning steps were performed before analysis:

- Checked the total number of records.
- Identified unique customers.
- Identified unique product categories.
- Detected missing (NULL) values.
- Removed incomplete records to improve data quality.

---

## 📊 Exploratory Data Analysis

The dataset was explored to understand:

- Customer demographics
- Product categories
- Sales distribution
- Monthly sales trends
- Customer purchasing behavior
- High-value transactions

---

 ## 📌 Business Problems Solved

This project answers the following business questions:

1. Retrieve all sales made on a specific date.
2. Find Clothing transactions with quantity greater than or equal to 4 during November 2022.
3. Calculate total sales and total orders for each product category.
4. Find the average age of customers purchasing Beauty products.
5. Retrieve transactions where total sales exceeded 1000.
6. Calculate the total number of transactions by gender and category.
7. Identify the best-selling month of each year based on average sales.
8. Find the Top 5 customers based on total sales.
9. Count unique customers in each product category.
10. Analyze sales performance across Morning, Afternoon, and Evening shifts.

---

## 💡 SQL Concepts Used

- Data Definition Language (DDL)
- Data Manipulation Language (DML)
- Filtering and Sorting
- Aggregate Functions
- GROUP BY
- CASE Expressions
- Common Table Expressions (CTEs)
- Window Functions
- Date and Time Functions
- Data Cleaning

---

## 📈 Key Insights

- Analyzed sales performance across multiple product categories.
- Identified top-performing customers based on total sales.
- Examined monthly sales trends to determine peak-performing months.
- Compared customer purchasing behavior across different demographics.
- Evaluated transaction distribution across Morning, Afternoon, and Evening shifts.

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/abutalha0649/retail-sales-analysis-sql.git
```

### 2. Open PostgreSQL

Launch pgAdmin and connect to your PostgreSQL server.

### 3. Create the Database

Execute the SQL script to create the database and retail_sales table.

### 4. Import the Dataset

Import the dataset into the retail_sales table.

### 5. Execute the Analysis Queries

Run the queries in `sql_project1.sql` to perform data cleaning, exploratory data analysis (EDA), and solve the business problems.

---

## 🚀 Project Highlights

- ✔ Built using PostgreSQL
- ✔ 10 real-world business problems solved
- ✔ End-to-end SQL analysis workflow
- ✔ Data cleaning and validation
- ✔ Exploratory Data Analysis (EDA)
- ✔ Demonstrates practical SQL skills for Data Analytics
- ✔ Portfolio-ready SQL project

---

## 🎓 Learning Outcomes

Through this project, I strengthened my understanding of:

- SQL Fundamentals
- Database Design
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Aggregate Functions
- Window Functions
- Business-Oriented SQL Queries
- Analytical Thinking

---

## 🔮 Future Improvements

- Build an interactive Power BI dashboard.
- Create SQL Views for reporting.
- Implement Stored Procedures.
- Optimize complex SQL queries.
- Perform advanced sales trend analysis.

---

## 👨‍💻 About Me

**Mohammad Abu Talha**

🎓 B.Tech (3rd Year)

📊 Aspiring Data Analyst 

I am a B.Tech (3rd Year) student with a strong interest in Data Analytics. I enjoy transforming raw data into meaningful insights using SQL and continuously improving my analytical skills through hands-on projects.

### Connect with Me

- **GitHub:** https://github.com/abutalha0649
- **LinkedIn:** https://www.linkedin.com/in/mohammadabutalha/

---

## ⭐ Support

If you found this project useful, please consider giving it a **Star ⭐** on GitHub.

Your support motivates me to build and share more Data Analytics projects.

---

**Thank you for visiting my project!**
