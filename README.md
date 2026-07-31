# SQL Portfolio — Retail Sales Performance Analysis

 A SQL project analyzing 3 months (April–June 2026) of retail sales data for a retail apparel business covering revenue, customer behavior, delivery performance, and payment trends. Includes 30 queries progressing from basic filtering to window functions,
 subqueries, and CTEs.

 ## 📄 SQL Portfolio Documentation

[🔗 Open SQL Portfolio Documentation PDF](./SQL_Portfolio_Documentation.Pdf)

# Objective

Answer common business questions using SQL which cities and categories drive revenue, how customers pay, how orders move through delivery stages while demonstrating a range of SQL techniques from basic to advanced.

 # Dataset
 
 [🔗 Open SQL Portfolio Dataset CSV](./sql_portfolio%20DATASET.csv)

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

# Dataset preview 
 ![Dataset Preview](SQL%20screenshots/Dataset%20preview.png)

 ## Sample Output
 ## 📊 SQL Analysis Screenshots

 ### Screenshots

**Total Revenue**


![Total Revenue](screenshots/Total%20Revenue.png)



**Top 5 Categories by Revenue**


![Top 5 categories by revenue](screenshots/Top%205%20categories%20by%20revenue.png)



**CASE Statements**


![CASE statements](screenshots/case%20statements.png)



**Subquery — Above-Average Spenders**


![Subquery - above-average spenders](screenshots/Subquery%20—%20above-average%20spenders.png)



**CTE — Top 3 Cities' Category-wise Revenue**


![CTE - Top 3 cities' category-wise revenue](screenshots/CTE%20—%20Top%203%20cities'%20category-wise%20revenue.png)



**Running Total (Window Function)**


![Running total window function](screenshots/Running%20total%20window%20function.png)
# Tools
**MySQL**
**Concepts**: 
filtering, aggregation, GROUP BY, CASE statements, window functions (RANK(), running totals), subqueries, CTEs

## Structure

Queries are grouped into four sections:

**Data Exploration & Filtering (Q1–11)
Aggregations & Grouping (Q12–21)
Business Insight Queries (Q22–26)
Advanced SQL — window functions, subqueries, CTEs (Q27–30)**
