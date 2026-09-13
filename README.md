# Northwind Sales & Business Performance Analysis

## 📊 Project Overview

This project analyzes sales and business performance using SQL and the Northwind Traders relational dataset.

The goal of the project is to transform raw transactional data into meaningful business insights related to:

- Sales performance
- Product performance
- Customer behavior
- Employee performance
- Shipping and operational efficiency

The analysis was performed using MySQL.

## 🛠️ Tools & Technologies

- MySQL
- SQL
- MySQL Workbench
- Git & GitHub

- ## 📁 Dataset

The project uses the Northwind Traders relational dataset, which contains transactional and business data across multiple related tables.

### Main Tables

- **Customers** — customer information and location
- **Orders** — order dates, employees, shipping details, and freight
- **Order Details** — products, quantities, prices, and discounts
- **Products** — product information and categories
- **Categories** — product category information
- **Employees** — employee information and roles
- **Shippers** — shipping company information

The dataset was imported into MySQL and analyzed using SQL queries designed around practical business questions.

## 🎯 Business Questions

The analysis was designed to answer practical business questions such as:

1. What are the company's total sales, orders, units sold, and average order value?
2. How does sales performance change over time?
3. Which months and years generate the highest revenue?
4. Which products generate the most revenue?
5. Which product categories perform best?
6. Who are the highest-value customers?
7. Which customers place orders most frequently?
8. Which employees generate the most sales?
9. Which shipping company handles the highest order volume?
10. What is the average shipping time?
11. What percentage of orders are shipped late?
12. Which shipping company has the highest late-delivery rate?
13. Which customers have never placed an order?
14. Which products have no recorded orders?

## 🧠 SQL Skills Demonstrated

This project demonstrates practical SQL techniques used for business analysis:

- SELECT, WHERE and ORDER BY
- Aggregate Functions
- GROUP BY and HAVING
- INNER JOIN
- LEFT JOIN
- CASE WHEN
- Subqueries
- Common Table Expressions (CTEs)
- Window Functions
- RANK()
- LAG()
- Date Functions
- Calculating business KPIs
- Percentage and growth calculations
- Multi-table relational analysis

- ## 🔍 Key Business Insights

### Sales Performance

- Total sales generated: **$1,265,793.04**
- Total orders analyzed: **830**
- Total units sold: **51,315**
- Average order value: **$1,525.05**

### Shipping Performance

- **Federal Shipping** had the lowest late-delivery rate at **3.61%**.
- **United Package** handled the highest number of shipped orders (**315**).
- **United Package** also had the highest late-delivery rate at **5.08%**.
- Overall, **37 out of 809 shipped orders** were late, resulting in a **4.57% late-order rate**.

### Customer Analysis

- **2 customers** had no recorded orders.
- Customer order frequency was analyzed to identify repeat customers and high-value customers.

- ## 💡 Business Recommendations

Based on the analysis, the following actions could help improve business performance:

1. **Monitor shipping reliability**  
   Investigate the higher late-delivery rate of United Package, especially because it handles the highest shipping volume.

2. **Focus on high-value customers**  
   Identify customers with high revenue and repeat purchases and develop strategies to improve retention.

3. **Investigate low-performing products**  
   Analyze products with low sales or no recorded orders to determine whether they should be promoted, repriced, or discontinued.

4. **Track sales trends**  
   Monitor monthly and yearly sales patterns to identify periods of strong or weak demand.

5. **Evaluate employee performance**  
   Use employee-level sales analysis to identify top performers and understand differences in sales contribution.


   ## 📂 Project Structure

```text
northwind-sales-analytics-sql/
│
├── README.md
│
├── sql/
│   └── Northwind_Traders_Corrected_MySQL.sql
│
├── data/
│   └── README.md
│
├── insights/
│   └── business_insights.md
│
└── screenshots/
    └── README.md

## 👩‍💻 Project Purpose

This project was created as a portfolio project to demonstrate practical SQL and business analysis skills for entry-level Data Analyst roles.

The focus is on turning relational business data into actionable insights using SQL.
