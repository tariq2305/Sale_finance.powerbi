# Sale_finance.powerbi
Sales & Financial Performance Dashboard

Project Overview
This project involves the creation of a comprehensive, interactive Power BI Dashboard designed to track and analyze the sales performance and financial health of a retail business. The goal was to transform raw transactional data into a strategic tool that identifies growth trends, profitability margins, and regional hotspots.

Key Features & Tasks Performed
Based on the project requirements, the following core tasks were successfully executed:

KPI Development: Established high-level metrics for Total Sales, Total Profit, and Growth using custom DAX measures.

Time-Series Analysis: Developed dynamic line charts to track revenue fluctuations from 2020 to 2025, identifying key seasonal peaks.

Interactive Slicers: Integrated multi-select filters for Category, State, and Payment Mode to allow for granular data exploration.

Executive Navigation: Designed a custom Sidebar Navigation Menu to provide a seamless "app-like" user experience across multiple report pages.

Geographic Visualizations: Leveraged map visuals to highlight regional performance, identifying New York as the lead revenue-generating hub.

Data Insights
Using the analyzed dataset ($6.18M Total Revenue), the dashboard revealed:

Top Performer: The Office Supplies category generated the highest volume ($2.09M).

Efficiency Leader: Furniture achieved the best overall profit margins at 26.5%.

Market Opportunity: Identification of underperforming regions, such as Ohio, for potential marketing intervention.

Technical Stack
Visualization: Power BI Desktop

Formulas: Data Analysis Expressions (DAX)

Data Cleaning: Python (Pandas) / Power Query

Reporting: Microsoft PowerPoint for Executive Summary

DAX Measures Used
A sample of the calculations implemented:

Total Sales: SUM('Sales Dataset'[Amount])

Profit Margin %: DIVIDE([Total Profit], [Total Sales], 0)

Safe Division: Utilized DIVIDE functions to ensure dashboard stability by handling zero-denominator errors.

How to Use
Clone the Repository: Download the .pbix file.

Open in Power BI: Ensure you have Power BI Desktop installed.

Interact: Use the sidebar menu to toggle between the Summary and Deep-Dive views.

Filter: Use the tiles at the top to filte
