# Power BI Project: Sales Analysis Dashboard

This project demonstrates sales data analysis using Power BI, integrating cloud-based data sources, and creating interactive dashboards for business insights.

---

## Key Features

- **Cloud Integration**: Data sourced from Azure Storage (`FACT_OrderDetails.csv`) and SQL Server (Customer table).
- **Data Modeling**: `1:many` relationship between Customers and Order Details using `CustomerID`.
- **Calculated Column**: Added `TotalSale` in `FACT_OrderDetails` for revenue analysis.

<p align="center"><img src="./screenshots/model.jpg" alt="Data Model" width="400"></p>

---

## Dashboards

### 1. CFO Dashboard

**Purpose**: Track business trends over time.

- Total sales and product quantities.
- Filters: Time and customer country.

<p align="center"><img src="./screenshots/1.cfo.jpg" alt="CFO Dashboard" width="500"></p>

---

### 2. Sales Performance

**Purpose**: Identify top-performing customers and countries.

- Country-wise and customer-wise performance.
- Detailed order information (date, quantity, discount, total sales).
- Filters: Time and customer country.

<p align="center"><img src="./screenshots/2.sales.jpg" alt="Sales Dashboard" width="500"></p>

---

### 3. Discount Analysis

**Purpose**: Assess discount patterns and impact on profitability.

- Average discount, total sales, and customer count by country.
- Interactive table for order metrics by customer and country.
- Filters: Time and country.

<p align="center"><img src="./screenshots/3.discounts.jpg" alt="Discount Analysis" width="500"></p>

---

This project showcases skills in data integration, modeling, and visualization to deliver actionable insights.
