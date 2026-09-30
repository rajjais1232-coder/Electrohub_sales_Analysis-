# ⚡ ElectroHub Sales Analysis Dashboard

<p align="center">

  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">

  <img src="https://img.shields.io/badge/Power%20Query-Data%20Transformation-217346?style=for-the-badge" alt="Power Query">

  <img src="https://img.shields.io/badge/DAX-Analytics-512BD4?style=for-the-badge" alt="DAX">

  <img src="https://img.shields.io/badge/Business%20Intelligence-Sales%20Analytics-0078D4?style=for-the-badge" alt="Business Intelligence">

</p>

<p align="center">
  <b>Interactive Power BI dashboard for analyzing ElectroHub sales, products, customers, orders, promotions, profit, and business performance.</b>
</p>

---

## 📌 Project Overview

**ElectroHub Sales Analysis** is an interactive **Business Intelligence and Data Analytics project** developed using Microsoft Power BI.

The project transforms raw sales transaction data into an interactive dashboard that helps analyze:

- Sales performance
- Profitability
- Product performance
- Customer behavior
- Order trends
- Quantity sold
- Promotion and discount patterns
- City-wise performance
- Time-based sales trends

The dashboard combines **Power Query, DAX, data modeling, KPI development, and interactive data visualization** to provide a comprehensive view of sales performance.

---

# 🎯 Business Objective

The primary objective of this project is to convert raw ElectroHub sales data into meaningful business insights.

The dashboard is designed to help answer important business questions such as:

- What are the overall sales and profit?
- Which products generate the highest sales?
- Which products generate the highest profit?
- Which products have the lowest performance?
- Which cities generate the most sales?
- How are sales changing over time?
- Which promotion categories provide higher discounts?
- What is the relationship between sales and profit?
- How does one selected period compare with another?
- Which orders contribute significantly to overall revenue?

---

# 📊 Dashboard Features

## 1. Executive Sales Overview

The executive dashboard provides a high-level summary of the business.

### Key KPIs

- 💰 Total Sales
- 💵 Total Profit
- 📦 Total Quantity Sold
- 🧾 Total Orders
- 📊 Average Order Value
- 🏷️ Average Discount
- 📈 Profit Margin

These KPIs allow users to understand the overall performance of ElectroHub at a glance.

---

# 📦 2. Product Analysis

The product analysis section focuses on identifying products that contribute significantly to sales, quantity, and profitability.

### Analysis Includes

- Top 5 products by sales
- Bottom 5 products by sales
- Top 5 products by profit
- Bottom 5 products by profit
- Products with highest quantity sold
- Product-level sales comparison
- Product-level profitability

### Business Questions

> Which products are generating the most revenue?

> Which products contribute the most profit?

> Are the highest-selling products also the most profitable?

---

# 📈 3. Sales Trend Analysis

The dashboard provides time-based sales analysis.

Sales can be analyzed by:

- Year
- Quarter
- Month
- Day

### Key Areas

- Monthly sales trends
- Yearly performance
- High-performing periods
- Low-performing periods
- Sales growth patterns
- Profit trends

This helps identify seasonal patterns and changes in business performance over time.

---

# 💰 4. Sales & Profit Analysis

Sales and profit are analyzed together to understand business profitability.

A scatter chart can be used to analyze:

**Sales vs Profit**

This allows users to identify:

- High-sales/high-profit products
- High-sales/low-profit products
- Low-sales/high-profit products
- Low-sales/low-profit products

This analysis can help identify areas that require further investigation.

---

# 🏷️ 5. Promotion & Discount Analysis

The project analyzes promotion categories and discounts.

### Analysis Includes

- Average discount
- Discount by promotion category
- Sales by promotion category
- Profit by promotion category
- Discount vs sales
- Discount vs profit

### Business Questions

- Which promotion category has the highest average discount?
- How are discounts distributed?
- Are heavily discounted orders generating strong sales?
- How does discounting relate to profitability?

> Discount and profit relationships should be interpreted together with product costs and other business factors.

---

# 🏙️ 6. City-Wise Sales Analysis

The dashboard provides geographical analysis of ElectroHub sales.

### Metrics

- Sales by city
- Profit by city
- Orders by city
- Quantity sold by city

This helps identify cities contributing significantly to overall sales and areas that may require further analysis.

Possible visualizations include:

- Bar charts
- Map visualizations
- Ranked tables
- KPI cards

---

# 📅 7. Two-Period Comparison

One of the interactive analytical features is the ability to compare two selected periods.

Users can compare:

| Metric | Period 1 | Period 2 |
|---|---:|---:|
| Sales | Dynamic | Dynamic |
| Profit | Dynamic | Dynamic |
| Quantity | Dynamic | Dynamic |
| Orders | Dynamic | Dynamic |

This allows analysis such as:

- Month vs Month
- Quarter vs Quarter
- Year vs Year
- Selected period vs selected period

### Example Questions

- How did sales change between two periods?
- Did profit increase or decrease?
- Did quantity sold change?
- Did order volume change?

---

# 🧾 8. Order-Level Analysis

The detailed order section allows users to move from high-level KPIs to individual transactions.

Possible fields include:

- Order ID
- Order Date
- Customer ID
- Product
- Product Category
- City
- Promotion Category
- Quantity
- Sales
- Profit
- Discount

Users can apply filters to investigate specific transactions.

---

# 🎛️ Interactive Dashboard Features

The dashboard is designed as an interactive Power BI report rather than a static collection of charts.

### Slicers

Possible slicers include:

- Date
- Product
- Product Category
- Customer
- City
- Promotion Category

### Cross Filtering

Selecting a product, city, promotion, or time period dynamically updates related visuals.

### Drill Down

Time-based analysis can follow:

```text
Year
 ↓
Quarter
 ↓
Month
 ↓
Day
