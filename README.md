# Coffee Sales Analysis

### Project Overview

This project focused on analysing coffee sales data spanning four years (2019–2022) to uncover business insights and support strategic decision-making. The primary goal was to evaluate sales performance over time, identify revenue trends, and understand seasonal fluctuations and product demand patterns.

### Data Sources

The primary data source for this project is the "Coffee Order Project.xlsx" which initially contains orders, customers and products worksheets.

### Tools

- Microsoft Excel [Download here](https://www.microsoft.com/en-gb/microsoft-365/excel)

### Steps

1. Data Enrichment – Customer Information
Used XLOOKUP to extract and populate relevant customer details; Customer Name, Email, Country, and Loyalty Card from the Customers table into the Orders table to enable customer-level analysis.

2. Data Enrichment – Product Details
Applied INDEX-MATCH function to retrieve product-related information; Coffee Type, Roast Type, Size, and Unit Price from the Products table and integrated them into the Orders table.

3. Sales Calculation - Created a new column, Sales, in the Orders table by multiplying Quantity and Unit Price, providing a basis for revenue analysis.

4. Enhanced Data Clarity - Added new columns; Coffee Type Name and Roast Type Name, to provide readable, full-text descriptions of the coffee types and roast types for better understanding.

5. Data Formatting - Properly formatted key columns such as Order Date, Size, Unit Price, and Sales to ensure consistency, readability, and accuracy in analysis.

6. Data Quality Checks - Performed checks for duplicate values to maintain data integrity and accuracy throughout the analysis.

7. Table Structuring - Converted the Orders dataset into an Excel Table format, enabling dynamic referencing and easier integration with PivotTables and charts.

8. Dashboard Creation – Coffee Sales Dashboard
Developed an interactive dashboard featuring: A line chart showing Total Sales Over Time, bar chart visualizing Sales by Country, bar chart highlighting the Top 5 Customers by Sales, A timeline, A Roast Type Name slicer, Size slicer and Loyalty Card slicer.

9. Interactive Visuals & Connectivity - Ensured all charts and visuals were interconnected, allowing for seamless filtering and exploration across different views and dimensions.

### Insights from Dashboard

- From the Sales by Country chart, the United States accounts for a significant portion of total sales (over $35,000), far outpacing Ireland ($6,697) and the United Kingdom ($2,799).
- The Top 5 Customers contribute relatively close revenue amounts, with Allis Wilmore and Brenn Dundredge generating the most sales.

### Recommendations

- Focus marketing and customer retention efforts on the U.S. market, as it has the highest revenue potential. Explore reasons for the lower sales in the UK and Ireland and consider targeted campaigns or partnerships in those regions to increase market share.
- Engage top customers through loyalty programs, exclusive offers, or personalized outreach. Encourage repeat purchases and seek feedback to improve the customer experience. Additionally, segment customer data to identify more potential high-value customers.


