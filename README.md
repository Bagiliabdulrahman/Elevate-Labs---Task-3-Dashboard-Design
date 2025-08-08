# Elevate Labs - Task 3: Dashboard Design

## Dataset: Sales & Financial Dataset
- Source: [Sales Financial Dataset](https://docs.google.com/spreadsheets/d/1to3LFd9oPVt--ruuxmVcOGLnDpuGS16-/edit?gid=437804108#gid=437804108)
- This dataset contains detailed information on sales, profit, manufacturing price, units sold, and customer/region segmentation. It is suitable for creating business dashboards and generating insights for decision-making.

## Objective
To design an interactive sales dashboard in Power BI for business stakeholders, enabling them to analyze sales performance, profit, and customer trends across various dimensions. The dashboard supports decision-making through interactive filters and clear KPIs.

## Tools Used
- Power BI (Desktop)
- Sales_Financial.csv (derived from Google Sheets source)

## Key Metrics (KPIs) Displayed
- Total Sales
- Total Profit
- Gross Sales
- Total Quantity

## Visualizations Created
- Sum of Manufacturing Price by Product (Bar Chart)
- Sum of Sales by Country (Bar Chart)
- Total Sales by Segment (Pie Chart)
- Total Sales and Units Sold by Customer Name (Combo Chart)
- Total Sales by Discount Band (Donut Chart)
- Slicers for Country, Customer Name, Year, and Month

## DAX Measures Used
- Total Sales = SUM(Sales[Sales])
- Total Profit = SUM(Sales[Profit])
- Gross Sales = SUM(Sales[Gross_Sales])
- Total Quantity = SUM(Sales[Quantity])

## Presentation (PPT) Summary
- File: Task3-Sales Financial Dashboard Design PPT
- Content:
  - Objective: Outlines the design of an interactive dashboard with KPIs and filters.
  - Dataset and Tools: Details the Sales & Financial Dataset and Power BI usage.
  - Key Metrics and Visualizations: Presents Total Sales (118.73M), Total Profit (16.89M), Gross Sales (127.93M), Total Quantity (1.13M), and listed visualizations.
  - Interactivity Features: Describes slicers for Country, Customer Name, Year (2021-2022), and Month (January, February, March, April), with time-series analysis.
  - Key Insights: Highlights Japan leading sales at 18.4M, VTT Amariila at 27.3K manufacturing price, and segment/discount band contributions.
  - Challenges and Solutions: Addresses incomplete March/April data and large dataset processing.
  - Conclusion and Recommendations: Suggests market focus, customer review, and future trend analysis.
- Note: Compile the LaTeX file in Overleaf with the dashboard screenshot inserted at the specified path.

## Dashboard Screenshot
![Sales Financial Dashboard](https://github.com/Bagiliabdulrahman/Elevate-Labs---Task-3-Dashboard-Design/blob/main/Screenshot%202025-08-08.png)
## Key Insights
- Japan leads sales at 18.4 million, followed by France at 17.7 million.
- VTT Amariila has the highest manufacturing price at 27.3 thousand.
- The largest segment contributes 42.43 million (35.74%) of total sales.
- The 0-5% discount band accounts for 34.63 million (29.17%) of sales.
- Jackson Hill achieves the highest sales at 5.3 million with 32.9 thousand units, while Mia Hill reports the lowest units at 18 thousand.
