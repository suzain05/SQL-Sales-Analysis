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

### 1. CASE Statements
![CASE Statements](/CASE%20Statements.png)

### 2. CTE
![CTE](/CTE.png)

### 3. Top 3 Cities' Category-wise Revenue
![Top 3 Cities Category-wise Revenue](/Top%203%20Cities%20Category-wise%20Revenue.png)

### 4. Running Total Window Function
![Running Total Window Function](/Running%20Total%20Window%20Function.png)

### 5. Subquery — Above-average Spenders
![Subquery Above Average Spenders](/Subquery%20Above-average%20Spenders.png)

### 6. Top 5 Categories by Revenue
![Top 5 Categories by Revenue](/Top%205%20Categories%20by%20Revenue.png)

### 7. Total Revenue
![Total Revenue](/Total%20Revenue.png)

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
