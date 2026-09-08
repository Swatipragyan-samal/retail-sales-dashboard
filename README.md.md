# Retail Sales Dashboard (Tableau)

An interactive Tableau dashboard analyzing retail sales performance by category,
top-selling items, and payment method — built on the same dataset cleaned in my
[retail-sales-data-cleaning](https://github.com/Swatipragyan-samal/retail-sales-data-cleaning)
project.

**Live Dashboard:** https://public.tableau.com/app/profile/swatipragyan.samal/viz/Retail_Sales_Dashboard_17888503062230/RetailSalesDashboard

## Business Problem

A retail business needs a quick, visual way to answer: which product categories
drive the most revenue, which individual items are top sellers, and how customers
prefer to pay. Raw spreadsheets don't answer these questions at a glance — a
dashboard does.

## Dataset

615 cleaned retail transactions across 8 categories (Beverages, Food, Milk
Products, Patisserie, Butchers, Electric Accessories, Computers, Furniture),
sourced from my Excel data-cleaning project.

## Dashboard Views

1. **Revenue by Category** — bar chart ranking all 8 categories by total revenue
2. **Top 10 Items** — the individual products generating the most revenue
3. **Revenue by Payment Method** — spend breakdown across Cash, Credit Card,
   Debit Card, and Mobile Payment

## Key Insights

- **Furniture** is the top revenue category by a wide margin, followed by
  **Computers**
- Revenue is fairly evenly split across all four payment methods — no single
  method dominates
- **Furn_Small_Table** and **Furn_Chair** are the top two individual items by
  revenue

## Tools Used

Tableau Public (bar charts, Top N filtering, dashboard layout), built on Excel-
cleaned source data

## What I'd Do Next

- Add a date filter to show revenue trends over time
- Add drill-down interactivity (click a category to filter the Top Items chart)
- Rebuild the same dashboard in Power BI to demonstrate both tools
