# Online Retail Sales Analysis — Excel Portfolio Project

## Overview

This project is an end-to-end sales analysis of an online retail dataset, built entirely in Microsoft Excel. It covers the full analytics workflow: cleaning raw transactional data, structuring it for analysis, building pivot tables and pivot charts, and delivering an interactive dashboard with slicers and a timeline filter. The final deliverable also includes a written business insights summary aimed at non-technical stakeholders.

The goal of this project is to demonstrate practical Excel-based data analysis skills — data cleaning, pivot-based summarization, dashboard design, and business communication — using a real-world style e-commerce dataset.

## Business Objective

The analysis was framed around questions a retail business stakeholder would realistically ask:

- What is the overall sales performance (revenue, invoice volume, average order value)?
- Which countries and markets drive the most sales?
- Which products contribute most to revenue?
- Are there seasonal or monthly sales patterns worth planning around?
- What actionable insights can be drawn to support business decisions?

## Dataset Description

The project uses an online retail transactional dataset containing invoice-level order records, including fields such as invoice number, product/stock code, description, quantity, unit price, invoice date, customer ID, and country.

The raw data required cleaning before analysis — including handling blank/invalid entries, removing duplicates, correcting data types, and standardizing fields — before it could be used for reliable pivoting and reporting.

**Note on data completeness:** The dataset's date range ends in December 2011, and December appears to have incomplete data (the month is not fully represented). Any apparent drop in sales for December should not be interpreted as a genuine seasonal decline without accounting for this data limitation.

## Tools Used

- **Microsoft Excel** — sole tool used for this project
- **Power Query** — data cleaning and transformation
- **Pivot Tables** — data summarization and aggregation
- **Pivot Charts** — visual representation of pivoted data
- **Slicers & Timeline** — interactive filtering controls for the dashboard
- **Excel Dashboarding** — combining charts, KPIs, and filters into a single interactive view
- **Business Insight Writing** — translating analysis into a stakeholder-facing summary

## Workbook Structure

The workbook is organized into the following sheets:

| # | Sheet Name | Purpose |
|---|------------|---------|
| 1 | Online Retail Raw Data | Original, unmodified dataset |
| 2 | Clean Sales Data | Cleaned and transformed data (via Power Query) used as the analysis base |
| 3 | Customers Sales Data | Sales aggregated and structured by customer |
| 4 | Sales by Country | Sales aggregated and structured by country |
| 5 | Invoice Summary | Invoice-level summary metrics |
| 6 | Pivots | All pivot tables used to power the dashboard and charts |
| 7 | Dashboard | Final interactive dashboard |
| 8 | Insights and Trends | Written business insights and observed trends |

## Dashboard Features

The dashboard consolidates key metrics and visuals into a single interactive view, including:

- Summary KPI cards (revenue, invoices, average invoice value, countries served)
- Sales breakdown by country (domestic vs. international)
- Top-performing products by revenue contribution
- Monthly/seasonal sales trend visualization
- **Slicers** for filtering by dimensions such as country and product
- **Timeline control** for filtering by invoice date/month

The dashboard is designed to let a viewer explore the data interactively rather than relying on static charts alone.

## Key Insights

- **Total Revenue:** $10.6M
- **Total Invoices:** 19,960
- **Average Invoice Value:** $533.17
- **Countries Served:** 38
- **Domestic Sales:** 90% of revenue
- **International Sales:** 10% of revenue
- **Peak Sales Period:** September to November
- **Top Products by Contribution:** DOTCOM POSTAGE, REGENCY CAKESTAND 3 TIER, and PAPER CRAFT LITTLE BIRDIE together account for approximately 47% of total sales

These figures indicate a business that is heavily concentrated in its domestic market, with a small number of products driving a disproportionately large share of revenue, and a clear seasonal peak in the final quarter (September–November) that likely aligns with pre-holiday buying patterns.

## Business Communication

Beyond the technical analysis, this project includes a dedicated **Insights and Trends** sheet that translates the pivot table and dashboard findings into plain-language business observations. This reflects a key part of real-world analyst work: presenting data findings in a way that is accessible to non-technical stakeholders and decision-makers, not just to other analysts.

## Skills Demonstrated

- Data cleaning and transformation using Power Query
- Structuring raw transactional data for analysis
- Building and organizing multiple pivot tables from a single data source
- Creating pivot charts for visual analysis
- Designing an interactive dashboard using slicers and a timeline
- Calculating and presenting key business metrics (revenue, average order value, market concentration)
- Identifying seasonal trends and product-level revenue concentration
- Communicating data insights in business-friendly language
- Attention to data quality caveats (e.g., recognizing incomplete date ranges) rather than over-interpreting results

## Conclusion

This project demonstrates a complete, self-contained Excel workflow for retail sales analysis — from raw data to a polished, interactive dashboard and a business-facing insights summary. It reflects practical, tool-based analytical skills that are directly applicable to entry-level and portfolio-stage data analyst roles, with an emphasis on accuracy, clear structure, and honest interpretation of the underlying data.
