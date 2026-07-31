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
 ![case statements](case statements.png)

![CTE - Top 3 cities' category-wise revenue](CTE — Top 3 cities' category-wise revenue.png)

![Running total window function](Running total window function.png)

![Subquery — above-average spenders](Subquery — above-average spenders.png)

![Top 5 categories by revenue](Top 5 categories by revenue.png)

![Total Revenue](Total Revenue.png)

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
