# E-commerce Sales Dashboard

### Dashboard Link : 


https://app.powerbi.com/groups/me/reports/a7c4a771-4b3b-4786-84ae-edf4d393eeb1?ctid=6082211e-6f08-438a-a87a-74cb477d9431&pbi_source=linkShare


This README documents the E-commerce Sales Dashboard, providing insights into sales performance, identifying key trends, and outlining the development process.

## Table of Contents

*   [Problem Statement](#problem-statement)
*   [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
*   [Dashboard Development](#dashboard-development)
*   [Key Metrics and Visualizations](#key-metrics-and-visualizations)
*   [Insights and Findings](#insights-and-findings)
*   [Tools Used](#tools-used)


## Problem Statement

E-commerce generates a significant amount of sales data. Without an effective way to visualize and analyze this data, it's difficult to:

*   Gain a holistic view of sales performance across different dimensions (e.g., region, product category, customer).
*   Identify trends, patterns, and anomalies in sales data.
*   Make data-driven decisions to optimize sales strategies and improve business outcomes.
*   Quickly identify top-performing and underperforming areas of the business.

This dashboard aims to address these challenges by providing an interactive and insightful overview of Madhav E-commerce's sales data.

## Data Cleaning and Preprocessing

*   **Handling Missing Values:** Addressing missing data in fields like customer addresses or product descriptions.
*   **Data Type Conversion:** Ensuring correct data types for calculations and visualizations (e.g., converting date strings to date objects).
*   **Data Transformation:** Calculating new metrics like Average Order Value (AOV) or profit margins.

## Dashboard Development

The dashboard was developed using Power BI. The development process involved:

1.  **Data Connection:** Connecting Power BI to the data source(s).
2.  **Data Modeling:** Creating relationships between tables to enable data analysis across different dimensions.
3.  **Visualization Creation:** Designing charts, graphs, and other visual elements to represent the data effectively.
4.  **Interactive Elements:** Implementing filters, slicers, and drill-down capabilities for user interaction.

## Key Metrics and Visualizations

Here's a breakdown of the key metrics and visualizations in the dashboard:

*   **Key Performance Indicators (KPIs):**

    *   **Sum of Amount (Total Sales):** 438K (Overall sales revenue)
    *   **Sum of Profit:** 37K (Total profit generated)
    *   **Sum of Quantity:** 5615 (Total number of items sold)
    *   **Sum of AOV (Average Order Value):** 121K (Average value of each order)

    ![KPIs](images/kpis.png)

*   **Sum of Amount by State:** Shows sales distribution across different states. Maharashtra, Madhya Pradesh, Uttar Pradesh, and Delhi are shown.

    ![Sales by State](https://github.com/user-attachments/assets/9a6af35e-4c75-4e0f-b071-aec7a764c3b4)

*   **% Of Quantity by Category:** Displays the proportion of items sold in each product category (Clothing, Electronics, Furniture). Clothing dominates at 62.62%.

    ![Quantity by Category](https://github.com/user-attachments/assets/ec04be83-02e9-4d59-8001-a9cb2a41db5f)

*   **Sum of Profit by Month:** Tracks profit trends over time, showing profitability for each month. There appears to be a loss in June.

    ![Profit by Month](https://github.com/user-attachments/assets/4a4d61c2-0d0a-4882-88b8-a3ba09a871d1)

*   **Sum of Amount by CustomerName:** Shows sales generated by top customers (Harivansh, Madhav, Madan Mohan, Shiva).

    ![Sales by Customer](https://github.com/user-attachments/assets/b7ddf998-2c4e-4312-b785-f8e10317fed6)

*   **% Of Quantity by Category (Detailed):** A more detailed breakdown of quantity by category and sub-category, along with payment mode information.

    ![Detailed Quantity by Category](https://github.com/user-attachments/assets/6bd9e790-72bd-4b15-8f4b-f1ad8f419720)

*   **Sum of Profit by Sub-Category:** Shows profit generated by different sub-categories. Printers appear to be the most profitable.

    ![Profit by Sub-Category](https://github.com/user-attachments/assets/52419400-6f99-4abb-a4db-fa4824268b1f)

## Insights and Findings

Based on the dashboard:

*   **Clothing is the top-selling category**, contributing significantly to overall sales.
*   **Tables are the most profitable sub-category.**
*   **June was a loss-making month**, requiring further investigation.
*   **Maharashtra appears to be a key market** in terms of sales amount.
*   **A few key customers (Harivansh, Madhav)** contribute a large portion of sales.

## Tools Used

*   **Data Visualization:** Power BI


## Snapshot Of Power BI Dashboard 
![Screenshot 2024-12-06 232729](https://github.com/user-attachments/assets/eeb6b4f1-7527-4c4e-9100-960d8caa19aa)

