# Sales-Data-Analysis-and-Dashboard

1. Project Overview
This project focuses on analyzing the sales performance of  Technova  Retail Pvt Ltd. for the year 2025. The objective is to identify key revenue drivers, analyze profit margins, and visualize insights through Excel PivotTables and a Power BI dashboard.
2. Dataset Description
The dataset contains sales transaction details for various products across four regions: East, North, South, and West.
Key columns:
  Date: Transaction date.
  Category: Product category - Electronics, Accessories, Furniture.
  Region: Geographic selling region.
  Product: Specific product name.
  Sales: Sales amount in currency.
  Profit: Profit earned from the sale.
  The dataset covers sales transactions from January to December 2025, representing daily sales records       across all regions.

3. Data Preprocessing and Cleaning 
The dataset was preprocessed and cleaned to ensure accuracy, consistency, and readiness for analysis.
•	Handling Missing Data: Missing numeric values (Sales, Profit) were replaced with category-wise averages, and missing categorical values (Region, Category) were filled using the mode.
•	Removing Duplicates: Deleted duplicate records using Date + Product + Region as unique keys.
•	Formatting Dates: Standardized date format to DD-MM-YYYY and derived Month and Quarter for time-based analysis.
•	Standardizing Text: Corrected inconsistent case and spacing in Category, Product, and Region names.
•	Converting Data Types: Ensured proper types — numeric for Sales/Profit, text for Category/Product/Region, and date for Date column.
•	Handling Outliers: Removed unrealistic values in Sales/Profit using statistical thresholds.
•	Feature Creation: Added new columns — Profit Margin (%) = (Profit ÷ Sales) × 100.
•	Validation: Verified total Sales and Profit after cleaning to confirm data integrity before visualization.

4. Data Exploration Using Pivot Tables
  Pivot tables were created to summarize key aspects of the data for insights:


Pivot Table	                  Purpose	Key Findings
1. Sales by Region	Total sales by each region
	South and East are leading sales

2.Sales by Region &                Category.	Shows the breakdown of sales by product category across all regions.	Accessories dominate sales overall, especially in South.
3.Monthly Sales Trend
	Aggregate monthly sales to detect trends	Sales peak around January, July, and September.
4.Sales by Product	Identify top-selling products	Bookshelf Prime, Chair Comfort, and Mouse Pad Pro emerged as the top-selling products.
5.Profit by Region	Profitability per region	East and South yield highest profits, correlating with sales.


5. Power BI Dashboard Overview
A Power BI dashboard was designed to visualize KPIs and trends for the year 2025. It provides an interactive view of total sales, profit margins, and top-performing products.

















6. Defined KPIs
The following KPIs were used to measure sales performance:
- Total Sales ($): Sum of all sales revenue across 2025.
- Total Profit ($): Aggregate profit for the year.
- Profit Margin (%): (Total Profit ÷ Total Sales) × 100.
- Top 5 Products by Sales.
- Regional Sales Performance.
- Monthly Growth Trend.
7. Key Findings and Recommendations
 Key Findings
•	Total Sales reached ₹503K with 14.8% overall profit margin.
•	East and North Regions generated the highest profit (₹20.2K).
•	Accessories dominated sales with 36% of total revenue.
•	Sales peaked in August (₹50K) with mid-year growth trends.
•	‘Mouse Pad Pro’ and ‘Chair Comfort’ were best-selling products.
•	Seasonal patterns indicate a clear surge in sales during Q4, driven by festive demand.

Recommendations
1.	Promote high-margin, low-sales products to maximize profit.
2.	Increase inventory in East and South regions with strong sales.
3.	Optimize pricing for Furniture category with lower margins.
4.	Launch marketing campaigns during August–October peak months.

8. Conclusion
This analysis of Technova Retail Pvt Ltd. sales data provided clear insights into performance across regions, products, and time periods.
After proper data cleaning and preprocessing, key trends such as high-performing regions, top products, and seasonal demand were identified.
The Excel and Power BI dashboards helped visualize KPIs effectively, enabling data-driven decisions.
Overall, this project shows how data analytics can improve business strategy and profitability.


