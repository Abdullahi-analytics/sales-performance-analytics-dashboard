# Sales Performance Analytics Dashboard

![Sales Performance Analytics Dashboard](Baslard%20Dashboard.png)

The dashboard provides a consolidated view of sales performance, highlighting key KPIs, regional performance, product performance, category performance, salesperson performance, and sales trends.

## Project Overview

The **Sales Performance Analytics Dashboard** is an Excel-based data analytics project designed to transform structured sales records into meaningful business insights.

The project analyzes sales performance across regions, cities, products, categories, salespersons, customer demographics, payment methods, and monthly trends. It combines data preparation, calculated fields, PivotTables, PivotCharts, KPI analysis, and dashboard visualization to present a clear view of sales performance and support data-driven decision-making.

## Business Objective

The primary objective of this project is to evaluate sales performance and identify the products, categories, locations, salespersons, payment methods, and periods contributing most to overall revenue.

The analysis is designed to answer questions such as:

- What is the overall sales performance?
- Which regions and cities generate the highest sales?
- Which products and categories contribute most to revenue?
- Which salespersons generate the highest sales?
- What are the monthly sales trends?
- Which payment methods are most frequently used?
- How do customer demographics relate to sales performance?
- Where are the strongest opportunities for improving sales performance?

## Dataset

The analysis contains **500 sales transactions** with 18 analytical fields after data preparation.

### Key Fields

| Field | Description |
|---|---|
| OrderID | Unique order identifier |
| OrderDate | Date of the transaction |
| Customer | Customer name/identifier |
| Gender | Customer gender |
| Age | Customer age |
| City | Customer city |
| Region | Sales region |
| Product | Product purchased |
| Category | Product category |
| Quantity | Units purchased |
| UnitPrice | Base unit price |
| Discount | Discount applied to the transaction |
| Salesperson | Sales representative responsible for the sale |
| PaymentMethod | Payment method used |
| Month | Derived month from OrderDate |
| Year | Derived year from OrderDate |
| Sales Price | Derived selling price |
| Total Sales Price | Calculated transaction sales value |

## Key Performance Indicators

The analysis produced the following headline metrics:

- **Total Sales:** 752,088.10
- **Total Quantity Sold:** 2,820 units
- **Total Orders:** 500
- **Average Order Value:** 1,504.18
- **Customers:** 48
- **Products:** 8
- **Categories:** 3
- **Regions:** 5
- **Cities:** 5
- **Salespersons:** 6
- **Payment Methods:** 4
- **Average Discount:** 7.15%

## Key Insights

### Regional Performance

**North Central** recorded the highest sales performance at **225,762.35**, followed by **South West** at **166,475.40**.

This indicates that North Central was the strongest regional contributor within the analyzed dataset.

### Product Performance

**Laptop** was the highest-performing product, generating **360,270.00** in sales.

It was followed by:

1. Laptop — 360,270.00
2. Phone — 171,737.50
3. Printer — 76,728.00
4. Desk — 51,544.00

### Category Performance

**Electronics** was the dominant product category, generating **633,598.00** in sales and accounting for the largest share of total revenue.

Furniture generated **84,993.00**, while Stationery generated **33,497.10**.

### Salesperson Performance

**Paul** recorded the highest sales among the six salespersons, generating **185,566.05** in sales.

### Monthly Performance

**March** recorded the highest monthly sales at **142,722.70**, while **June** recorded the lowest at **102,119.65** within the analyzed period.

### Payment Methods

**Cash** generated the highest sales value at **241,869.20**, while card payments recorded the highest number of orders at **135**.

## Data Preparation & Analysis Process

The project followed a structured analytical workflow:

1. Reviewed and organized the initial sales dataset.
2. Prepared the analysis-ready sales table.
3. Created derived fields including **Month**, **Year**, **Sales Price**, and **Total Sales Price**.
4. Applied calculated values to support sales analysis.
5. Built PivotTables to summarize sales performance.
6. Created PivotCharts to visualize key dimensions.
7. Developed KPIs for high-level performance monitoring.
8. Designed an Excel dashboard to consolidate the major findings.
9. Interpreted the results to identify sales trends and performance drivers.

## Dashboard

The final dashboard provides a consolidated view of sales performance and allows the major findings to be communicated through visual analysis.

## Project Structure

```text
sales-performance-analytics-dashboard/
│
├── data/
│   └── sales_dataset.csv
│
├── excel/
│   └── sales_performance_analysis.xlsx
│
├── images/
│   ├── sales-performance-dashboard.png
│   ├── sales-data.png
│   ├── pivot-analysis-1.png
│   ├── pivot-analysis-2.png
│   └── pivot-analysis-3.png
│
└── README.md
