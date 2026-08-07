# 📊 Ecom Express Power BI Dashboard

## Project Overview

This project is an interactive **Power BI dashboard** developed to analyze the sales performance of an e-commerce company, **Ecom Express**. It provides insights into revenue, order trends, product performance, cancellations, and state-wise sales to support data-driven business decisions.

---

## Business Problem

Managing large volumes of sales data manually makes it difficult to track business performance and identify trends. This dashboard helps stakeholders monitor key metrics, analyze sales patterns, and make informed decisions through interactive visualizations.

---

## Dataset

The project uses three datasets:

- Customers.csv
- Orders.csv
- Products.csv

---

## Data Cleaning

The following transformations were performed using **Power Query**:

- Removed the unnecessary last column from the Customers table.
- Created a custom **Operating System** column (Apple → iOS, Others → Android).
- Capitalized all state names.
- Merged First Name and Last Name into a single **Customer Name** column.

---

## Dashboard KPIs

- Total Revenue
- Average Order Value
- Total Orders
- Cancellation Rate
- Revenue Lost Due to Cancellations

---

## Dashboard Features

- Revenue by Product
- Revenue by Category
- Revenue by State
- Quarterly Revenue Trend
- Product Category Filter
- Purchase Date Filter

---

## Tools Used

- Power BI
- Power Query
- DAX
- CSV Datasets

---

## Dashboard Preview

![Dashboard](Images/Dashboard.png)

---

## Repository Structure

```text
Ecom-Express-PowerBI-Dashboard/
│
├── Dashboard/
├── Dataset/
├── Images/
├── Report/
└── README.md
```

---

## Author

**Amlan Biswal**

GitHub: https://github.com/aamlan15