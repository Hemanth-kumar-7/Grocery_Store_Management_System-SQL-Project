# Grocery Store Management System | SQL Data Analysis Project

## Overview
This project focuses on retail data analysis for a Grocery Store Management System using MySQL to uncover valuable business insights.  
The analysis explores multiple aspects of store operations — including customer behavior, sales performance, supplier efficiency, and employee productivity — through advanced SQL queries and meaningful data interpretation.

The goal of this project is to demonstrate the ability to clean, structure, and query relational databases to solve real-world business problems and provide data-driven recommendations for improving performance.

---

## Project Objectives
The project was designed with the following objectives:

- Identify top-performing suppliers based on product variety, pricing, and total revenue contribution.  
- Evaluate employee performance by analyzing the number and total value of orders processed.  
- Examine sales trends across products, categories, and time periods.  
- Understand customer purchasing patterns to improve retention and engagement.  
- Generate data-backed recommendations for optimizing operations and profitability.

---

## Database Design
The database was structured to reflect key relationships within a retail system:

- A **Supplier** can provide many **Products**.  
- A **Category** can include multiple **Products**.  
- Each **Product** can appear in several **Order Details** records.  
- An **Order** can contain multiple **Order Details** entries.  
- A **Customer** can place multiple **Orders**.  
- An **Employee** can process multiple **Orders**.  

### Tables in the Database
- **Supplier** – Contains supplier details and contact information.  
- **Categories** – Defines different product categories.  
- **Employees** – Stores employee information such as names, roles, and hire dates.  
- **Customers** – Holds customer details and demographics.  
- **Products** – Includes product information linked to both supplier and category.  
- **Orders** – Contains order-level data linked to customers and employees.  
- **Order_Details** – Tracks individual product transactions associated with each order.  


---

## Key Business Questions Answered

### Customer Analysis
- How many unique customers placed orders?  
- Who are the top five customers by total purchase value?  
- What is the average purchase amount per customer?  

### Product Analysis
- Which products have the highest total sales volume?  
- How do sales vary by product category and supplier?  
- What is the total revenue per product?  

### Supplier Analysis
- Which suppliers contribute the most to total revenue?  
- What is the average product price by supplier?  
- Which supplier provides the widest range of products?  

### Employee Analysis
- Which employees handled the most orders?  
- What is the total and average sales value processed per employee?  

### Sales and Order Trends
- What are the monthly and weekday/weekend sales trends?  
- What is the average order value and total order count?  

---

## Key Insights
- The top five customers account for more than 60% of total revenue, indicating a highly loyal customer base.  
- Certain product categories are consistently more profitable, suggesting targeted investment opportunities.  
- Weekend sales are slightly higher than weekday sales, highlighting consumer behavior trends.  
- Seasonal spikes in demand reveal ideal months for running promotions and discounts.  
- Top-performing suppliers and employees significantly influence total sales performance.  
- A positive correlation exists between order quantity and total revenue, emphasizing the benefits of bulk sales.

---

## Recommendations
- Introduce a loyalty program to reward and retain high-value customers.  
- Focus marketing efforts on top-performing categories and peak sales months.  
- Strengthen partnerships with high-revenue suppliers for better pricing and supply reliability.  
- Recognize and reward top-performing employees to encourage continued excellence.  
- Offer bulk purchase discounts to increase order volume and average sales value.

---

## Tools and Technologies Used
- **Database:** MySQL  
- **Query Language:** SQL (DDL & DML)  
- **Analysis Techniques:** Aggregations, Joins, Subqueries, and Common Table Expressions (CTEs)  
- **Visualization:** PowerPoint and PDF summaries for business reporting  
- **Key Skills:** Data Modeling, Data Cleaning, Query Optimization, and Business Insight Derivation

---

## Challenges Faced
- Some date fields were stored as text (`VARCHAR`), requiring conversion using `STR_TO_DATE()` for accurate time-based analysis.  
- Joining multiple tables without duplication demanded careful management of foreign keys and grouping logic.  
- Writing nested queries (e.g., average order value per customer) required optimization for performance.  
- Query performance on large datasets was improved through indexing and optimized joins.

---

## Conclusion
This project delivers a complete analytical view of grocery store operations, transforming raw transactional data into actionable insights.  

It demonstrates the ability to:
- Design and structure a normalized relational database.  
- Write efficient analytical SQL queries.  
- Translate findings into strategic business recommendations.  
Overall, this project highlights how SQL-based data analysis can empower smarter, data-driven decision-making in the retail sector.
