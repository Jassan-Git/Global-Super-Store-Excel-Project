# Excel Store Sales Analysis

This project analyzes store sales and performance data to derive actionable insights and visualize them using an interactive Excel dashboard. The dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/apoorvaappz/global-super-store-dataset), and the analysis answers key questions about customer behavior, product performance, and sales trends. Each insight is supported by dedicated sheets in the Excel file containing relevant charts and calculations.

## Table of Contents
1. [Overview](#overview)
2. [Data Cleaning and Preparation](#data-cleaning-and-preparation)
3. [Customer Analysis](#customer-analysis)
4. [Product Analysis](#product-analysis)
5. [Sales Performance and Forecasting](#sales-performance-and-forecasting)
6. [Interactive Dashboard](#interactive-dashboard)
7. [How to Use](#how-to-use)
8. [Installation](#installation)
9. [Contributing](#contributing)
10. [License](#license)

---

## Overview

The goal of this project is to explore sales data, uncover trends, and provide a comprehensive understanding of store performance. Key questions addressed include:
- Customer purchase patterns and profitability.
- Product performance across regions and categories.
- Sales growth trends and future estimates.

The Excel dashboard integrates buttons linking to detailed sheets, making it easy to navigate insights and visualize data.

---

## Data Cleaning and Preparation

To ensure accurate analysis, the dataset was cleaned and formatted:
- **Date Formatting:** Replaced `"-"` with `"/"` in `Order Date` and `Ship Date` columns and standardized the format to `MM/DD/YY`. Converted these columns to date types.
- **Column Removal:** Dropped unnecessary columns (`Postal Code` and `Product ID`) to focus on relevant data.

---

## Customer Analysis

### Key Insights:
1. **Customer Frequency Profiling:**
   - Frequency categories:
     - **High Frequency:** 40+ purchases.
     - **Medium Frequency:** 20-39 purchases.
     - **Low Frequency:** Less than 20 purchases.
   - ~42% of unique customers are high-frequency buyers and contribute **78% of total revenue**.
   - Low-frequency customers (44% of total) generate only **10% of revenue**.

2. **Profitability by Frequency:**
   - Average profit per order:
     - High Frequency: **$32.36**
     - Medium Frequency: **$23.34**
     - Low Frequency: **$14.86**

3. **Customer Segmentation:**
   - The **Consumer segment** is the most profitable across all years, followed by Corporate and Home Office.

4. **Geographical Distribution:**
   - Most customers and orders are from the **United States**, with order volumes 100x the average per country.

---

## Product Analysis

### Key Insights:
1. **Top Sales by Country:**
   - **United States** leads with over **$2.3M** in total sales, followed by **Australia** with **$925k**.

2. **Top Profit-Making Product Types:**
   - **Copier** consistently ranks as the top profit-making product type, except in 2011, where **Phones** led.

3. **Price vs. Sales:**
   - Analysis reveals that sales increase with price decreases on a daily level.

4. **Delivery Times:**
   - Regions **Central, South, North, and EMEA** exhibit the highest delivery delays.

---

## Sales Performance and Forecasting

- Sales have shown consistent growth, averaging **24% year-over-year**.
- Forecast: Sales are estimated to exceed **$5M next year**, continuing the upward trend.

---

## Interactive Dashboard

The Excel file includes a dashboard with buttons linking to individual sheets for each analysis. Each sheet contains:
- Detailed calculations.
- Charts and graphs supporting insights.
- A Home Button to navigate back to the Home sheet.

This design ensures easy navigation and a seamless user experience.

---

## Acknowledgments

- Dataset sourced from [Kaggle](https://www.kaggle.com/).
- Special thanks to the Excel community for inspiring interactive dashboard designs.
