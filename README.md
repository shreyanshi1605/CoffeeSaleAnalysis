# Coffee Sale Analysis - Excel Project

# Project Overview:

This Excel-based dashboard provides a comprehensive analysis of coffee sales across various regions and customer segments. It tracks sales trends, top-performing customers, and highlights the impact of roast type, coffee size, and loyalty programs. The dashboard also offers interactive filtering options for real-time data exploration.


### Project Workflow:

1. Data Preparation:
   - XLOOKUP: Used the `XLOOKUP` function to retrieve specific sales data based on product and roast type, which enhanced the speed of analysis.
   - INDEX MATCH: Applied `INDEX MATCH` for flexible lookups in cases where multi-criteria searches were required, further improving data accuracy.
   - Multiplication Formula for Sales: Calculated sales totals by multiplying the quantity sold by the unit price, ensuring precise tracking of sales, with total sales of **$35,639** in the United States.

2. Advanced Conditional Logic:
   - Multiple IF Functions: Created conditional logic to flag high-value sales, categorize customers, and handle missing data, enhancing the data’s interpretability.

3. Data Formatting:
   - Date Formatting: Standardized dates to ensure smooth analysis over time, particularly useful for sales trends visualization.
   - Number Formatting: Applied currency formatting to all sales figures, ensuring clear representation of amounts, such as **$6,697** from Ireland and **$2,799** from the United Kingdom.

4. Data Cleaning:
   - Check for Duplicates: Identified and removed duplicate sales records, ensuring data integrity and avoiding skewed results.
   - Convert Range to Table: Structured the data by converting ranges to tables, enabling easy manipulation, sorting, and filtering.

5. Visual Analysis with Pivot Tables & Charts:
   - Pivot Tables and Pivot Charts: Created pivot tables to aggregate data, and pivot charts to visualize:
   - Top 5 Customers: The highest spender, **Allis Wilmore**, contributed **$317**, followed by **Brenn Dundredge** at **$307**.
   - Total Sales Over Time: Displayed monthly sales trends for different coffee types (Arabica, Excelsa, Liberica, Robusta) between **2019** and **2022**, with a peak sale of nearly **$900** in early **2021**.
   - Formatting Pivot Tables and Charts: Applied conditional formatting to highlight significant changes in sales data.
   - Insert Timeline: Added a timeline to dynamically filter data by month and year, making it easier to track sales growth over time.
   - Insert Slicers: Created slicers for roast type, coffee size, and loyalty card to allow for more specific data filtering.

6. Dashboard Optimization:
   - Updating Pivot Table Data: Ensured that the dashboard dynamically updates as new data is imported, reflecting real-time changes in the charts and tables.

### Key Insights from the Dashboard:

- Total Sales Over Time: Sales data for different coffee types (Arabica, Excelsa, Liberica, Robusta) shows peaks and troughs, with a notable spike in **February 2021** where sales reached nearly **$900**.
- Sales by Country: The United States generated the highest sales at **$35,639**, followed by Ireland with **$6,697**, and the United Kingdom with **$2,799**.
- Top 5 Customers: The highest-paying customer is **Allis Wilmore** with a total spend of **$317**, followed by **Brenn Dundredge** with **$307**.

### Technologies Used:
- Excel Functions: XLOOKUP, INDEX MATCH, IF, multiplication formulas.
- Data Visualization: Pivot Tables, Pivot Charts, Timelines, and Slicers.

### Screenshot:
![image](https://github.com/user-attachments/assets/4234f31d-b049-4b38-8b8c-12ac0fbb3dc6)

This Coffee Sales Dashboard project showcases Excel’s powerful data analysis and visualization capabilities, helping stakeholders track sales performance, customer engagement, and regional sales distribution.
