# SQL Portfolio — Retail Sales Performance Analysis

 A SQL project analyzing 3 months (April–June 2026) of retail sales data for a retail apparel business covering revenue, customer behavior, delivery performance, and payment trends. Includes 30 queries progressing from basic filtering to window functions,
 subqueries, and CTEs.

 ## 📄 SQL Portfolio Documentation

[🔗 Open SQL Portfolio Documentation PDF](./SQL_Portfolio_Documentation.Pdf)

# Objective

Answer common business questions using SQL which cities and categories drive revenue, how customers pay, how orders move through delivery stages while demonstrating a range of SQL techniques from basic to advanced.

 # Dataset
 
 [🔗 Open SQL Portfolio Dataset CSV](./sql_portfolio%20DATASET.csv)


 | Column | Description |
|---|---|
| OrderID, CustomerID, CustomerName | Order and customer identifiers |
| Gender | Customer gender |
| Category | Product category |
| City | Delivery city |
| DeliveryStatus | Delivered / Processing / Shipped |
| Price, Qty, Revenue | Order value fields |
| PaymentMethod | Cash / UPI / Net Banking |
| CustomerRating | 1–5 rating |
| Date, Month | Order date |

**Column**                                    **Description**

OrderID, CustomerID, CustomerName	         - Order and customer identifiers
Gender                                     -Customer gender
Category                                   -Product category
City	                                      -Delivery city
DeliveryStatus	                            -Delivered / Processing / Shipped
Price, Qty, Revenue                        -Order value fields
PaymentMethod	                             -Cash / UPI / Net Banking
CustomerRating                             -1–5 rating
Date, Month                                 -Order date


## 🛠 SQL Concepts Used

- SELECT
- WHERE
- GROUP BY
- ORDER BY
- HAVING
- INNER JOIN
- LEFT JOIN
- Aggregate Functions
- CASE WHEN
- Subqueries


# Dataset preview 
 ![Dataset Preview](SQL%20screenshots/Dataset%20preview.png)

 ## Sample Output
 
 ## 📊 SQL Analysis Screenshots
 
 # 1. TOTAL REVENUE 
![Total Revenue](SQL%20screenshots/Total%20Revenue.png)

# 2. TOP 5 CATEGORIES BY REVENUE
![Top 5 categories by revenue](SQL%20screenshots/Top%205%20categories%20by%20revenue.png)

# 3. CASE STATEMENTS
![CASE statements](SQL%20screenshots/case%20statements.png)

# 4. SUBQUERY ABOVE AVERAGE SPENDERS
![Subquery - above-average spenders](SQL%20screenshots/Subquery%20—%20above-average%20spenders.png)

# 5. CTE TOP 3 CITIES CATEGORY WISE REVENUE
![CTE - Top 3 cities' category-wise revenue](SQL%20screenshots/CTE%20—%20Top%203%20cities'%20category-wise%20revenue.png)

# 6. RUNNING TOTAL(WINDOW FUNCTION)
![Running total window function](SQL%20screenshots/Running%20total%20window%20function.png)

**MySQL**
**Concepts**: 
filtering, aggregation, GROUP BY, CASE statements, window functions (RANK(), running totals), subqueries, CTEs

# ER DIAGRAM

![ER Diagram](https://raw.githubusercontent.com/suzain05/SQL-Sales-Analysis/main/SQL%20screenshots/ER_Diagram.png)

## Structure

Queries are grouped into four sections:

**Data Exploration & Filtering (Q1–11)
Aggregations & Grouping (Q12–21)
Business Insight Queries (Q22–26)
Advanced SQL — window functions, subqueries, CTEs (Q27–30)**

## 📝 SQL Problems Solved

- Total Revenue Calculation
- Revenue by Category
- Revenue by City
- Monthly Revenue Analysis
- Top 5 Categories by Revenue
- CASE Statement for Sales Classification
- Running Total using Window Functions
- Subquery – Above Average Spenders
- CTE – Top 3 Cities Category-wise Revenue
- Aggregate Functions (SUM, AVG, COUNT)
- GROUP BY & HAVING
- Joins

## Related Project

This dataset is also used in an Excel dashboard project covering the same 3-month period with pivot tables, charts, and a full visual dashboard.

**Fathima Suzain · Data Analytics Portfolio · 2026**
