Revenue Analysis 

Overview

This project involves the analysis of retail transaction data to evaluate sales performance across different regions, product categories, and customer segments. The goal is to derive actionable insights regarding revenue drivers and regional strengths.

File Structure

1. Data Sources

* Revenue_Analysis.xlsx : The primary dataset containing raw transaction logs.

* Columns: OrderDate, Transaction_ID, Customer_Name, Product_Item, Region, Units_Sold, Unit_Price, Revenue.

* Revenue_Analysis.xlsx : A supplementary summary sheet (likely a Pivot Table export) showing aggregated revenue totals for specific regions.

2. Analysis Output

* sales_report.md: The final comprehensive report generated from the data. It contains:

* Executive Summary

* Key Performance Indicators (KPIs)

* Regional & Product Performance Tables

* Customer Insights & Strategic Recommendations

Key Findings Summary

* Total Revenue: $4,525 (Jan 5 – Jan 10, 2024).

* Top Region: West (53% of total revenue).

* Top Product: Laptops (Highest revenue generator).

* Top Volume: Keyboards (Highest quantity sold).

Methodology

The analysis was performed using Execl to:

1. Clean and aggregate the raw data.

2. Calculate total revenue, unit counts, and average order values.

3. Group data by Region and Product_Item to identify trends.

4. Generate the structured Markdown report.
How Excel Is Used

The core of this project relies on Revenue_Analysis.xlsx to handle data management and preliminary analysis. The workflow is divided into two distinct components:

1. Raw Data Management (Sheet: yes)

This sheet acts as the transactional ledger. It stores granular data for every individual sale.

Columns Used: OrderDate, Transaction_ID, Customer_Name, Product_Item, Region, Units_Sold, Unit_Price, and Revenue.

Calculations: The Revenue column is derived using the formula:

$$Revenue = Units\_Sold \times Unit\_Price$$

2. Aggregation & Pivot Tables (Sheet: Sheet1)

This sheet is used for summarizing the raw data into high-level metrics.

Pivot Table Functionality: It aggregates the Revenue data by Region.

Current State: The sheet currently highlights the South region's performance ($175 Total Revenue), providing a quick-view dashboard for specific regional queries without needing to filter the raw data manually.
How to Use

1. Review sales_report.md for a detailed breakdown of the business performance.

2. Refer to the raw data files if granular transaction details are needed for validation.
