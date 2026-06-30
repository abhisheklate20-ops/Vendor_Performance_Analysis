# Vendor_Performance_ Analysis

A retail vendor performance and procurement analytics project built on transactional data spanning 79 stores, 126 vendors, and 67 cities, designed to uncover inefficiencies in pricing, freight costs, and inventory turnover, and to support data-driven procurement decisions.

## 1.	Problem Statement

Retail businesses operating across multiple stores and vendor relationships often lack visibility into vendor performance, pricing efficiency, and inventory health. Without structured analysis, issues like supplier concentration risk, loss-making transactions, slow-moving inventory, and inconsistent margins go undetected, leading to suboptimal procurement decisions.

## 2.	Objective

To conduct a comprehensive vendor performance analysis identifying key patterns in procurement, sales, and inventory data, surfacing actionable insights that improve vendor management, profit margins, and overall business performance.

## 3.	Tech Stack
•	Python (Pandas, SQLAlchemy, Matplotlib/Seaborn) · SQL (SQLite).<br>
•	📊 Power BI Desktop – Main data visualization platform used for report creation.<br>
•	📂 Power Query – Data transformation and cleaning layer for reshaping and preparing the data.<br>
•	🧠 DAX (Data Analysis Expressions) – Used for calculated measures, dynamic visuals, and conditional logic.<br>

## 4.	What This Project Covers
•  Data ingestion pipeline: Raw CSV data ingested into a SQLite database using Python (Pandas, SQLAlchemy) with logging for traceability.
•  Exploratory Data Analysis: Distribution analysis, outlier detection, and summary statistics across pricing, sales, and inventory metrics.
•  Vendor & brand performance analysis: Identification of top vendors/brands by sales, supplier concentration (Pareto analysis), and procurement contribution.
•   Inventory & profitability analysis: Stock turnover evaluation, unsold inventory capital lock-up by vendor, and identification of loss-making transactions.
•  Statistical analysis: Correlation analysis between pricing, sales, and profitability metrics, plus confidence interval comparison between top- and low-performing vendors.
•  Power BI dashboard: An interactive dashboard summarizing key KPIs (total sales, purchases, gross profit, unsold capital) along with vendor/brand performance visuals.

## 5.	Key Insights
•  Procurement is concentrated among a small set of vendors (top 10 vendors contribute ~66% of total purchases), posing supplier concentration risk.
•  Certain transactions show negative gross profit, pointing to underpriced or loss-making sales.
•  Bulk purchasing reduces unit cost by ~72%, highlighting an opportunity to negotiate better terms.
•  Low-performing vendors maintain notably higher profit margins (40–43%) than top performers (30–32%), suggesting pricing/volume trade-off opportunities.

## 6.	Screenshots
https://github.com/abhisheklate20-ops/Vendor_Performance_Analysis/blob/main/Dashboard%20for%20Project-1.png
