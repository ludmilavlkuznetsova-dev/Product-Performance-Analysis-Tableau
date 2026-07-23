# Product Performance Analysis Dashboard

## Project Overview

An interactive Tableau dashboard designed to analyze sales performance, product profitability, and category contribution in a retail business.

The purpose of this project is to create a business-oriented analytics solution that helps stakeholders monitor key performance indicators, identify profitable and unprofitable products, and explore sales performance across different product categories.

---

## Dashboard Preview

![Product Performance Dashboard](files/dashboard preview.png)

---

# Business Problem

A retail business needs a clear overview of product performance to answer key analytical questions:

- How are sales changing over time?
- Which categories and sub-categories generate the highest sales?
- Which products contribute most to profitability?
- Which products generate losses?
- How can users analyze performance of a specific product?
- How do discounts affect overall sales performance?

---

# Dashboard Objectives

The dashboard allows users to:

- Monitor overall sales and profitability metrics
- Analyze sales trends over time
- Identify top and bottom performing products
- Explore sales distribution across categories and sub-categories
- Drill down from category level to sub-category level
- Analyze individual product performance using filters

---

# Dataset

**Dataset:** Superstore Sales Dataset

**Main table:** Orders

**Time period:** 2016–2019

## Main Fields

| Field | Description |
|------|-------------|
| Order Date | Date of customer order |
| Category | Product category |
| Sub-Category | Product sub-category |
| Product Name | Individual product |
| Sales | Revenue generated |
| Profit | Profit generated from sales |
| Quantity | Number of items sold |
| Discount | Discount applied to orders |

---

# Dashboard Structure

## 1. KPI Overview

The dashboard includes five key performance indicators:

- **Sales** — total revenue generated during the selected period
- **Profit** — total profit generated from sales
- **Profit Margin** — profitability ratio showing profit as a percentage of sales
- **Quantity** — total number of items sold
- **Average Discount** — average discount applied to orders

These metrics provide a quick overview of business performance and help evaluate the relationship between sales volume, profitability, and discount strategy.

---

## 2. Sales Trend Analysis

### Purpose

Analyze sales dynamics over time and identify seasonal patterns.

### Features

- Monthly sales trend visualization
- Year filtering
- Comparison of sales performance across selected years

### Business Value

Helps identify sales patterns and understand how revenue changes over time.

---

## 3. Product Profitability Analysis

### Purpose

Identify the most and least profitable products.

### Features

- Top 10 products by profit
- Bottom 10 products by profit
- Interactive product analysis

### Business Value

Helps identify products that drive profitability and products that may require further investigation.

---

## 4. Category & Sub-Category Analysis

### Purpose

Understand sales contribution across product groups.

### Features

- Category-level analysis
- Drill-down to sub-category level

### Business Value

Allows users to identify the main sales drivers and explore product group performance in more detail.

---

## 5. Product-Level Analysis

### Purpose

Analyze performance of a specific product.

### Features

- Product filter
- Interactive dashboard updates

### Business Value

Allows users to investigate individual products without analyzing the entire dataset.

---

# Technical Implementation

## Tableau Features Used

- Interactive dashboards
- Calculated fields
- Parameters
- Filters
- Dashboard actions
- Hierarchical drill-down
- KPI cards
- Custom formatting and dashboard layout

## Calculated Metrics

Examples:

**Profit Margin**
SUM(Profit) / SUM(Sales)

**Average Discount**
AVG(Discount)

---

# Key Insights

*(To be completed after final analysis)*

Examples:

- Technology category generates the highest sales contribution.
- Some products generate high sales but have low or negative profitability.
- Discount levels may affect product profitability.
- Product performance varies significantly within the same category.

---

# Tools & Technologies

- Tableau Public
- Microsoft Excel

---

# Project Structure
Product-Performance-Analysis-Tableau/

│
├── README.md
│
├── screenshots/
│   └── dashboard.png
│
├── data/
│   └── superstore_orders.xlsx
│
└── tableau/
└── Product_Performance_Dashboard.twbx

---

# Skills Demonstrated

- Data visualization
- Business analysis
- Sales performance analysis
- Product profitability analysis
- Dashboard design
- KPI development
- Tableau:
  - Calculated fields
  - Parameters
  - Filters
  - Dashboard actions
  - Hierarchies

---

# Tableau Public

Interactive dashboard:

[Add Tableau Public Link]

---

# Author

Ludmila Kuznetsova

Data Analytics Portfolio Project
