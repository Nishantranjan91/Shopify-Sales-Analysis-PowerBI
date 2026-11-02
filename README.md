# Shopify Sales Analysis | Power BI Dashboard

## Project Overview

This project presents an end-to-end analysis of Shopify sales data using Microsoft Power BI. It was developed as part of a data analytics internship practice assignment.

The objective is to analyze sales performance, customer purchasing behavior, product performance, and data quality through interactive dashboards.

## Tools & Technologies

- Microsoft Power BI Desktop
- Power Query — Data cleaning and transformation
- DAX — Measures and KPI calculations
- Data Modeling — Relationships and star-schema design
- GitHub — Project documentation and version control

## Dataset Overview

The dataset contains Shopify sales transaction records covering **March 18–24, 2025 (7 days)**.

The analysis includes sales transactions, customer IDs, order details, product types, geographical information, and transaction dates.

### Data Model

The Power BI model includes four tables:

- **FactSales** — Main transaction fact table
- **DimCustomer** — Customer dimension
- **DimDate** — Date dimension
- **DimProductType** — Product category dimension

Relationships connect the dimension tables to FactSales.

## Key Performance Indicators

| KPI | Result |
|---|---|
| Total Sales | $4.60M |
| Total Orders | Approximately 7K |
| Total Customers | Approximately 4K |
| Average Order Value | $618.89 |
| Repeat Customers | 46.02% |
| One-Time Customers | 53.98% |

## Dashboard 1 — Sales Performance

This dashboard provides an overview of Shopify sales activity.

### Features

- Total Sales, Orders, Customers, and Average Order Value
- Sales by Product Type
- Sales by City
- Daily Sales Trend
- Orders by Product Type

### Key Findings

- Running Shoes generated approximately **$1.62M**, making them the highest-revenue product category.
- Tennis Shoes and Walking Shoes were also major revenue contributors.
- Sales varied across the seven-day analysis period.

## Dashboard 2 — Customer Analysis

This dashboard analyzes customer purchasing patterns.

### Features

- Top Customers by Order Count
- Top 10 Customers by Sales
- Repeat vs One-Time Customers
- Repeat Customers KPI
- Interactive Date Slicer

### Key Findings

- Approximately **46.02%** of customers were classified as repeat customers within the analyzed data.
- Approximately **53.98%** were one-time customers.
- Customer purchasing frequency and spending varied across customers.

## Dashboard 3 — Data Quality Check

This dashboard validates selected critical transaction fields.

| Data Quality Metric | Missing Records |
|---|---|
| Missing Customer IDs | 0 |
| Missing Order Numbers | 0 |
| Missing Order Dates | 0 |

These results indicate no missing values in the three checked fields for the analyzed records. They do not represent a comprehensive data-quality audit.

## DAX Measures

The project uses DAX measures for:

- Total Sales
- Total Orders
- Total Customers
- Average Order Value
- Orders per Customer
- Repeat Customers
- One-Time Customers
- Customer Ranking
- Missing-value checks

## Dataset Limitations

The dataset covers only **seven days (March 18–24, 2025)**.

Therefore:

- Long-term customer retention cannot be reliably measured.
- Cohort analysis is limited.
- Customer Lifetime Value (CLV) cannot be reliably estimated.
- Conclusions reflect the available reporting period rather than long-term business performance.

## Project Files

- [Power BI Dashboard (.pbix)](Shopify_Sales_Analysis_Final.pbix)
- [Dashboard Report (.pdf)](Shopify_Sales_Analysis_Final.pdf)

## How to View the Project

1. Download the `.pbix` file from this repository.
2. Install Microsoft Power BI Desktop.
3. Open the `.pbix` file to explore the interactive report.
4. Alternatively, view the PDF for a static overview of the dashboards.

## Conclusion

This project demonstrates practical skills in Power Query, DAX, data modeling, dashboard development, sales analysis, customer segmentation, and data-quality validation.

**Project Type:** Data Analytics Internship Assignment

**Author:** Nishant Ranjan
