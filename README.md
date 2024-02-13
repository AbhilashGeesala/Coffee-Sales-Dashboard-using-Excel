# Coffee-Sales-Dashboard-using-Excel

The Coffee Bean Sales Dataset provides a comprehensive exploration of the coffee industry.

The main goals are to pinpoint top customers, monitor coffee-type sales trends, and analyze country-specific sales, empowering the dashboard to facilitate customer engagement, loyalty strategies, product optimization, and geographical expansion efforts.

Requirements for the solution include the development of a user-friendly and visually appealing dashboard with interactive visualizations to facilitate trend identification.

The Coffee Sales Dashboard aims to provide actionable insights for enhancing sales, improving customer satisfaction, and driving strategic expansion efforts.

The data retrieval from the Customers Table involves using the VLOOKUP formula, while the INDEX and MATCH functions are combined for extracting information from the Products Table. This approach ensures a uniform formula for consistent data extraction across all table columns.

Column Treatment and Adjustments:

1. Email Column: Replaced missing values with an empty cell using an IF statement.
2. Sales Column: Calculated sales by multiplying Quantity and Unit Price.
3. Coffee Type Name Column: Introduced a new column mapping abbreviations (Rob, Exc, Ara, Lib) to full names (Robusta, Excelsa, Arabica, Liberica) using a Nested IF function for better clarity.
4. Roast Type Name Column: Employed a similar approach to replace abbreviations (M, L, D) with full roast-type names (Medium, Light, Dark).
5. Order Date Column: Transformed the month component from a numeric to a categorical value to address date format variations.
6. Size Column: Appended the unit "kg" uniformly to each row for metric value notation.
7. Unit Price and Sales Column: Updated to currency format with the addition of the $ symbol.
8. Loyalty Card: Added a new column indicating whether the customer has a loyalty card or not.

Pivot Table & Dashboard:

1. Created a "TotalSales" pivot table, initially grouped by years, later adjusted for monthly and yearly granularity for detailed sales trend visualization.
2. Added "Coffee Type Name" and "Sales" columns to the pivot table for Y-axis plotting against dates, providing insights into sales quantities on specific dates and different coffee types.
3. Inserted a formatted 2D Line Chart for visual representation.
4. Integrated a Timeline feature from PivotChart Analyzer for dynamic analysis of specific timeline segments, enhancing precision and focused exploration.
5. Inserted 3 Slicers for Size, Roast Name Type, and Loyalty Card for enhanced data filtering.

Established seamless connections between slicers and visual elements, ensuring applied filters reflect across associated graphs and representations.





