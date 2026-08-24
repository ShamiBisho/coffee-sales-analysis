Interactive Excel dashboard analyzing coffee shop sales, customer behavior, product performance, and revenue trends.
# Coffee Sales Analysis & Dashboard

## Overview

An Excel-based data analysis project analysing approximately 1,000 coffee shop orders across the United Kingdom, Ireland, and the United States.

The project explores sales performance, customer behaviour, product performance, and profitability, with the findings presented through an interactive Excel dashboard.

## Business Questions

The analysis focuses on questions such as:

- Which markets generate the most revenue?
- Is the UK a weaker market in total sales and on a per-customer basis?
- Which coffee types generate the highest profit margins?
- How does revenue change over time?
- Do customers with loyalty cards generate different levels of revenue?
- Which products and markets represent the strongest opportunities?

## Dataset

The dataset contains approximately 1,000 orders with information relating to:

- Order and customer information
- Country
- Coffee type
- Roast type
- Order quantity
- Revenue
- Profit
- Loyalty-card status
- Customer purchasing behaviour

### Markets

- United Kingdom
- Ireland
- United States

### Coffee Types

- Arabica
- Excelsa
- Liberica
- Robusta

## Tools & Techniques

- Microsoft Excel
- Data Cleaning
- Excel Formulas
- SUMIFS / COUNTIFS / IF functions
- PivotTables
- Data Aggregation
- KPI Analysis
- Profit Margin Analysis
- Customer Analysis
- Data Visualisation
- Dashboard Design

## Dashboard

![Coffee Sales Dashboard](images/dashboard-preview.png)

The dashboard provides an overview of key business metrics and allows sales performance to be explored across different dimensions.

Key metrics and visualisations include:

- Total Revenue
- Total Profit
- Total Orders
- Average Order Value
- Revenue by Month
- Revenue by Country
- Profit Margin by Coffee Type
- Top-performing Products

## Key Findings

The analysis identified several differences in performance across markets and products.

- The United States generated the highest average revenue per active customer among the three markets.
- Ireland also generated higher average revenue per active customer than the United Kingdom.
- Liberica had the highest profit margin among the four coffee types, at approximately 13%.
- Robusta had the lowest profit margin, at approximately 6%.
- Loyalty-card customers did not generate higher average revenue per active customer than non-loyalty customers in this dataset.

## Recommendations

Based on the analysis:

1. Investigate the factors contributing to stronger customer revenue in the US and Ireland and assess whether similar strategies could be applied in the UK.
2. Review pricing, costs, and product mix for lower-margin coffee types such as Robusta.
3. Evaluate the effectiveness of the current loyalty programme rather than assuming loyalty-card membership directly increases customer value.
4. Continue monitoring monthly and market-level sales performance to identify changes in demand.

## Project Structure

```text
coffee-sales-analysis/
│
├── Coffee-Sales-Analysis-Dashboard.xlsx
├── README.md
└── images/
    └── dashboard-preview.png
