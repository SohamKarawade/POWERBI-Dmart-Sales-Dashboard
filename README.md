# 📊 D-Mart Sales Dashboard – Power BI Project

## 📝 Project Overview

This Power BI dashboard provides a comprehensive analysis of D-Mart's sales performance using interactive visualizations. It integrates order and transaction data to help track key business metrics, identify trends, and uncover actionable insights.

---

## 📁 Data Sources

### 1. `Orders.csv`
Includes:
- Order ID
- Order Date
- Customer Name
- State
- City

### 2. `Details.csv`
Includes:
- Order ID
- Amount
- Profit
- Quantity
- Category
- Sub-Category
- Payment Mode

---

## 🔗 Data Model

Both tables are connected via `Order ID` to enable accurate aggregation and filtering across the dataset. A new calculated field, **Average Order Value (AOV)**, is derived as:
AOV = Amount / Quantity

---

## 📈 Dashboard Features

### 🔹 KPIs:
- Total Sales (Amount): ₹438K
- Average Order Value (AOV): ₹121K
- Total Quantity Sold: 5615
- Total Profit: ₹37K

### 🔹 Visualizations:
- **Amount by State** (Bar Chart)
- **Top Customers by Amount** (Bar Chart)
- **Quantity by Category** (Donut Chart)
- **Quantity by Payment Mode** (Donut Chart)
- **Profit by Month** (Trend Bar Chart)
- **Profit by Sub-Category** (Bar Chart)

### 🔹 Filters:
- Quarter Selector
- State Selector

---

## 🎯 Key Insights

- Identify top-performing states and customers
- Understand product demand by category
- Analyze profit trends monthly
- Evaluate payment mode preferences
- Drill into state-level and time-based sales performance

---

## 🛠️ Tools & Skills

- Power BI Desktop
- Data Modeling & Relationships
- DAX Calculations
- Data Visualization & Design
- Interactive Slicers & Filters

---
