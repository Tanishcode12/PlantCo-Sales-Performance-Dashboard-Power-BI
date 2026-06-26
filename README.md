# PlantCo-Sales-Performance-Dashboard-Power-BI
Built an interactive Power BI dashboard to analyze sales, profitability, and customer performance using Power Query, DAX, and a star schema data model. Features dynamic KPI switching, YTD vs PYTD analysis, drill-down reports, conditional formatting, and customer segmentation for business insights.
## Dashboard Preview
<img width="671" height="375" alt="image" src="https://github.com/user-attachments/assets/1b527408-1151-4ff1-9df7-26b0a9d26bfb"/>

## Project Objectives
The goal of this project was to simulate a real-world business reporting solution by:
- Importing and transforming raw Excel data
- Building a star schema data model
- Creating reusable DAX measures
- Designing dynamic KPI cards
- Developing interactive reports with drill-down capabilities
- Implementing advanced Power BI techniques including SWITCH measures and dynamic title
## Dataset
The project uses three Excel tables:
### Fact Table
Sales transactions including
- Invoice Date
- Product ID
- Account ID
- Quantity Sold
- Sales Revenue
- Cost of Goods Sold (COGS)
### Product Dimension
Contains
- Product Family
- Product Group
- Product Name
- Product Type
- Product Size
### Customer Dimension
Contains
- Account ID
- Country
- Postal Code
- Address
- Latitude / Longitude
### Data Model
The report follows a Star Schema. 
                 Dim Date
                    |
                    |
Dim Product ---- Fact Sales ---- Dim Account
## Power Query
Data preparation included
- Cleaning column names
- Removing duplicate keys
- Setting appropriate data types
- Creating dimension tables
- Building a Date table
- Creating helper columns for YTD calculations
## DAX Features
The dashboard includes numerous reusable DAX measures including:
- Total Sales
- Gross Profit %
- Quantity Sold
- Year-to-Date (YTD)
- Prior Year-to-Date (PYTD)
- YTD vs PYTD Comparison
- Dynamic SWITCH Measures
- Dynamic Report Titles
## Dashboard Features
### Executive KPI Cards
Displays
- YTD Sales
- PYTD Sales
- YTD vs PYTD
- Gross Profit %
Includes conditional formatting to quickly highlight positive and negative performance.
### Dynamic Metric Selector
Users can instantly switch the dashboard between
- Sales
- Gross Profit
- Quantity
without rebuilding visuals.
### Sales Trend Analysis
Interactive combo chart showing
- Monthly performance
- Quarterly drill-down
- Current Year vs Prior Year comparison
### Bottom Performing Countries
Treemap highlights the Bottom 10 countries based on YTD vs PYTD performance to quickly identify declining markets.
### Waterfall Analysis
Explains how each month contributes to the overall variance between current and previous year performance.
### Customer Profitability Analysis
Scatter plot segments customers based on
- Gross Profit %
- Sales Volume
allowing businesses to identify
- High-profit / Low-sales customers
- High-volume / Low-profit customers
- Strategic growth opportunities
## Skills Demonstrated
### Business Intelligence
- Dashboard Design
- KPI Reporting
- Data Visualization
- Executive Reporting
### Power BI
- Power Query
- DAX
- Data Modeling
- Star Schema
- Relationships
- Conditional Formatting
- Drill Through
- Dynamic Titles
- Bookmarks
- Slicers
### Data Analysis
- Trend Analysis
- Profitability Analysis
- Customer Segmentation
- Geographic Analysis
- Performance Monitoring
## Business Insights
The dashboard helps answer questions such as
- Which countries are experiencing declining sales?
- How does current performance compare to last year?
- Which customer segments generate the highest profit?
- Which product categories contribute the most revenue?
- Where should sales teams focus future efforts?
## Technologies Used
- Power BI Desktop
- Power Query
- DAX
- Microsoft Excel
