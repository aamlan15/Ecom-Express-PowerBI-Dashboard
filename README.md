# Ecom Express Power BI Dashboard

## Project Overview

This project is an interactive Power BI dashboard developed to analyze the sales performance of an e-commerce company, **Ecom Express**. The dashboard provides insights into revenue, customer orders, product performance, cancellations, and sales trends to support data-driven business decisions.

## Business Problem

Analyzing large volumes of e-commerce sales data manually is time-consuming and inefficient. This dashboard enables users to monitor key business metrics, identify sales trends, and evaluate business performance through interactive visualizations.

## Dataset

The project uses three datasets:

- Customers.csv
- Orders.csv
- Products.csv

## Data Cleaning & Transformation

The following transformations were performed using **Power Query**:

- Removed unnecessary columns from the Customers table.
- Created a custom **Operating System** column (Apple → iOS, Others → Android).
- Standardized state names by capitalizing all entries.
- Merged First Name and Last Name into a single **Customer Name** column.
- Verified data types and prepared the data model for analysis.

## Dashboard KPIs

- Revenue
- Average Order Value (AOV)
- Total Orders
- Cancellation Rate
- Revenue Lost Due to Cancellations

## Dashboard Features

- Revenue by Product
- Revenue by Product Category
- State-wise Revenue Analysis
- Quarterly Revenue Trend
- Product Category Filter
- Purchase Date Filter
- Interactive KPI Cards

## Tools & Technologies

- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- CSV Files

## Repository Structure

```text
Ecom-Express-PowerBI-Dashboard/
│
├── Customers.csv
├── Orders.csv
├── Products.csv
├── Ecom Express Dashboard.pbix
├── Dashboard.png
├── Ecom Express Dashboard Report.pdf
└── README.md
```

## Author
Amlan Biswal
B.Tech,Engineering Physics
Delhi Technological University, Delhi
**Amlan Biswal**

GitHub: https://github.com/aamlan15
