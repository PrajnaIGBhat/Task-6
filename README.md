# Task 6: Sales Trend Analysis Using Aggregations

## 🎯 Objective
To analyze monthly revenue and order volume over time using SQL aggregations.

## 🧰 Tools Used
- **Database Engine:** MySQL
- **Dataset:** `cleaned_superstore_data` (adapted from Sample Superstore)
- **Fields Used:**
  - `order_date`: Date of the order
  - `sales`: Revenue from each order
  - `order_id`: Unique identifier for each order

## 📝 SQL Script Overview
The SQL query:
- Extracts the **year** and **month** from `order_date`
- Calculates:
  - `SUM(sales)` → total revenue per month
  - `COUNT(DISTINCT order_id)` → total unique orders per month
- Groups the data by year and month
- Orders the result chronologically

## 🔍 Outcome
This task demonstrates how to:
- Use `GROUP BY`, `SUM()`, `COUNT(DISTINCT ...)`, and date extraction functions
- Identify sales trends and seasonal patterns in transactional data



