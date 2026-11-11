# Blinkit Orders Dashboard

An Excel dashboard practice project built around a synthetic quick-commerce order dataset. The project is intended for practicing data cleaning, KPI development, PivotTables, charts, slicers, and business analysis.

> **Data note:** This is synthetic, computer-generated practice data inspired by the quick-commerce business model. It is not real or official Blinkit data.

## Dashboard overview

The dashboard presents an operational and commercial view of order performance, including:

- Total revenue
- Gross profit and gross margin
- Total orders and average order value
- Cancellation rate and cancellation reasons
- On-time order rate
- Average customer rating
- Monthly revenue trends
- Revenue contribution by city
- Monthly revenue and gross profit comparison
- Hourly order patterns
- Promised versus actual delivery time by city

The workbook dashboard also includes interactive City and Category slicers.

## Workbook contents

The Excel workbook is designed with the following worksheets:

| Worksheet | Purpose |
|---|---|
| `Blinkit_Orders` | Order-level dataset with 12,000 records and 30 fields |
| `Data_Dictionary` | Definitions and data types for the dataset columns |
| `Dashboard` | Interactive Excel dashboard |
| `Sheet2` | Additional worksheet retained from the source workbook |

## Dataset fields

The order-level data includes order dates and times, city and dark store, customer segments, product categories, basket values, discounts, delivery fees, coupon usage, payment mode, platform, order status, delivery performance, customer ratings, cancellation reasons, revenue, and gross profit.

Some useful business definitions:

- **Revenue:** `Order_MRP - Discount_Amount + Delivery_Fee` for delivered orders; zero for cancelled orders.
- **Gross Profit:** `(Order_MRP - Discount_Amount) × category margin` for delivered orders.
- **Average Order Value:** Revenue divided by total orders, subject to the dashboard's calculation logic.
- **On-Time Orders:** Orders meeting the promised delivery time.

## Tools and skills

- Microsoft Excel
- PivotTables and PivotCharts
- Slicers
- KPI calculations
- Dashboard design and data visualization
- Business and operational analysis

## Project objective

Practice turning order-level data into a clear business dashboard, identify trends across time and cities, and evaluate sales, profitability, delivery, and cancellation performance.

## File

The source workbook is intended to be stored in this repository as:

`Blinkit_Orders_Dashboard_Data.xlsx`

