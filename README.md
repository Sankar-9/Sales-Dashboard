# Sales-Dashboard

## Short Description
A comprehensive, interactive Power BI dashboard designed to analyze global sales performance, profitability, and shipment distributions for Awesome Chocolates. This project provides a top-down view of key business metrics over a multi-year period, empowering stakeholders to make data-driven decisions regarding product pricing, regional focus, and sales team management.

## Tech Stack
* **Data Visualization & Analytics:** Power BI
* **Data Transformation:** Power Query
* **Calculations:** DAX (Data Analysis Expressions)

## Data Source
* The dataset used for this dashboard is the **Awesome Chocolates** dataset, sourced from the GitHub repository of [chandoo.org](https://chandoo.org/).

## Features and Highlights
* **Dynamic KPI Ribbon:** High-level tracking of Total Amount ($140M), Total Boxes (9M), Shipment Count (25K), Total Profit ($81M), and an impressive Profit Percentage of 57.38%.
* **CY vs. PY Trend Analysis:** Time-series line charts comparing Current Year (CY) and Previous Year (PY) metrics for both Sales Amount and Boxes sold, highlighting seasonal trends and year-over-year growth.
* **Geographical Revenue Breakdown:** A donut chart visualizing market share across six major regions, prominently featuring top-performing countries.
* **Distribution Analytics:** A histogram mapping the frequency and volume distribution of shipments.
* **Salesperson Performance Matrix:** A detailed leaderboard of the Top 6 salespersons (e.g., Ponnan, Suman) featuring profile pictures, total revenue generated, and conditionally formatted profit percentage data bars.
* **Product Profitability Tracking:** Treemaps for the Top 6 products by revenue, coupled with a comprehensive product table that uses conditional formatting (red/green data bars) to instantly flag high-margin items vs. loss-making products.

## Example
By interacting with the global date slicer located at the top right (e.g., adjusting the range to focus purely on late 2024 to early 2025), a user can dynamically cross-filter the entire dashboard. This allows regional managers to instantly see which salespersons drove the most profit during that specific time window, and which products trended in specific geographical markets like India or the USA.

## Key Questions Answered
* How is the business performing this year compared to the same period last year?
* Which global markets are contributing the highest share of the overall $140M revenue?
* Who are the top-performing sales representatives in terms of both volume (boxes) and profitability?
* What are our highest-grossing products, and are there any products negatively impacting the overall profit margin?
* What is the typical size and distribution of our product shipments?

## Business Insights
* **Market Dominance:** India is the leading geographical market, contributing 28.53% ($40M) to the total revenue, closely followed by New Zealand and Australia.
* **Profitability Red Flags:** While the overall profit margin is strong at 57.38%, the product-level breakdown reveals that specific items, such as *85% Dark Bars* (-35.24%) and *Baker's Choco Chips* (-2.55%), are operating at a loss. These require immediate strategic review for pricing adjustments or cost optimization.
* **Sales Leadership:** A significant portion of revenue is driven by top performers like Ponnan ($11.7M) and Suman ($10.4M), who maintain strong profit margins above 50%, establishing a benchmark for the rest of the sales team.
* **Top Products:** *Organic Choco Syrup* ($12M) and *Caramel Stuffed Bars* ($10M) are the primary drivers of product revenue, indicating a strong consumer preference for these categories.

## Screenshots / Demos
See how the dashboard looks like ![Dashboard](https://github.com/Sankar-9/Sales-Dashboard/blob/main/Snapshot%20of%20Dashboard.png)
