# Sales Distribution Interactive Dashboard (Power BI)

**Tools used:** Power BI (data modeling, DAX, interactive visuals) · Power Query (data cleaning & transformation)

## 📌 Overview

An interactive Power BI dashboard analyzing sales distribution across time, products, customers, and regions. Built to explore how a business can track performance against monthly targets, identify top customers and products, and understand regional/geographic sales concentration — with dynamic filtering for decision-making support.

*Dataset note: built on a public sales-distribution practice dataset (not proprietary company data), used here to demonstrate end-to-end dashboard design — data cleaning, modeling, DAX measures, and visual storytelling.*

![Dashboard Preview](./screenshots/dashboard-overview.png)
📂 [Dashboard file (.pbix)](./Dashboard.pbix) · [Source data (.xlsx)](./Sales-Distribution-Data-File.xlsx)

## 🧹 Data Preparation

The raw dataset included three tables — transaction-level sales, monthly targets, and customer-region mapping. Cleaning and shaping was done in **Power Query**:
- Date formatting standardized across the transaction table
- Missing value checks performed
- New calculated columns added to support clearer visuals
- Column renaming for clarity and consistent naming conventions

## ❓ Research Questions

The dashboard was designed to answer:
1. What is the total sales amount over the selected period?
2. Who are the top 3 customers by total purchase value?
3. Which regions contribute most to overall sales?
4. How do monthly sales perform against targets?
5. What are the product-wise sales figures and their trends?

## 📊 Dashboard Design

**Top section**
- Month slicer for dynamic filtering
- Total Sales card (dynamic, updates with filters)
- Top 3 Customers card
- Region-wise donut chart

**Middle section**
- Region slicer
- Monthly Sales vs. Target combo chart (column + line)

**Lower section**
- Weekly area chart — tracks performance spikes/dips over time
- Product-wise clustered bar chart
- Interactive map visual — country-level sales distribution

*(8 visuals total: 2 slicers, 1 card, 1 multi-row card, 1 combo chart, 1 area chart, 1 clustered bar chart, 1 donut chart, 1 map)*

## 🔍 Key Insights

- **Total sales** exceeded 984K over the analyzed period, with clear month-to-month variation
- **Top customers**: Customer 22, 23, and 33 led in purchase volume
- **Regional performance**: Western and Northeast regions dominated overall sales
- **Targets vs. actuals**: sales met or exceeded targets in several months but underperformed in others — highlighting where forecasting/planning could improve
- **Top products**: Products 30, 41, and 44 were the best-selling
- **Weekly patterns**: sales showed recurring peaks early in the month
- **Geographic reach**: sales activity spanned North America, Asia, and Europe

## 🧾 Takeaway

The dashboard demonstrates how combining Power Query data cleaning with Power BI's visual and filtering capabilities turns raw transactional data into an operational decision-making tool — surfacing which customers, products, and regions drive performance, and where actual results diverge from targets.

---
📫 [LinkedIn](https://www.linkedin.com/in/wadud-rahman)
