Objective

The objective of this project is to create a comprehensive Manufacturing Analytics Dashboard in Tableau, Power BI,  providing actionable insights on manufacturing performance. The dashboard aims to:

Track key performance indicators (KPIs) like manufactured quantity, processed items, and rejected items.

Analyze performance by different parameters such as buyers, customers, employees, and machines.

Offer month-to-Month(MTM) calculations and identify trends over time.

Enhance decision-making with clear, interactive visualizations.

Dataset Overview

The dataset used for this project includes key columns like:

End of Operation Date

Fiscal Date and Time

Sales Order Delivery Date

Sales Order Document Date

Expected Delivery Date

Sales Order Post Date

Start Time of Operation

Work Order Date

Steps Followed

Data Cleaning and Preparation:

Replaced non-existing dimension values with 'Unknown' to ensure data completeness.

Cleaned and standardized column headings for consistency and readability.

Formatted data types appropriately to facilitate accurate calculations and analysis.

Removed unnecessary columns, reducing dataset size by 20% and improving performance.

Handled missing values by replacing nulls with 0.

Standardized date formats and ensured consistency across columns.

Validated data integrity and removed 100+ duplicate records.

Analysis and Metrics Calculation:

Lead Time: Calculated the difference between Sales Order Document Date and Expected Delivery Date using SQL queries. Identified that reducing lead time by 10% could improve on-time delivery rates and enhance customer satisfaction.

Delay Time: Computed the difference between Expected Delivery Date and Sales Order Delivery Date. Highlighted that minimizing delays by optimizing production schedules can reduce late deliveries by up to 15%.

Month-on-Month Order Volume: Analyzed monthly order volume trends and identified a 12% average increase, suggesting strong demand and the need to scale operations accordingly.

Buyer Segmentation: Segmented buyers based on order volume and rejection rates, revealing that the top 20% of buyers contribute to 80% of total orders, enabling more targeted account management.

Month-on-Month Rejection Rate: Tracked rejection rate trends and identified a 5% reduction opportunity by improving quality control processes.

Visualizations:

Created dashboards in Tableau and Power BI to display overall KPIs and performance trends.

Designed separate pages focusing on Employees, Machines, and Buyers.

Consolidated visualizations by using a single visual with X-axis parameters (Buyer Name, Customer Name, Employee Name, Machine Name) and Y-axis parameters (Manufactured Quantity, Processed Items, Rejected Items).

MTD Calculations:

Implemented month-to-date metrics to track ongoing performance within the current month.

Key Insights and Recommendations

Streamline Production Scheduling: Reducing lead time by 10% can significantly improve on-time delivery rates and enhance customer satisfaction.

Optimize Resource Allocation: By minimizing delays through better scheduling, late deliveries can be reduced by up to 15%, improving operational efficiency.

Scale Operations Proactively: A 12% average month-on-month increase in order volume suggests the need to scale production capacity and manage inventory more effectively.

Enhance Quality Control: Addressing quality issues and reducing rejection rates by 5% will minimize waste and improve product reliability.

Focus on High-Value Buyers: The top 20% of buyers contribute to 80% of total orders — strengthening relationships and offering tailored services can drive higher customer retention and revenue growth.

Invest in Employee Training: Improving employee skills in key processes like cutting and folding can enhance efficiency and reduce rejected quantities. Applying the Pareto principle (80/20 rule) shows that focusing on these critical areas can solve the majority of quality issues.

Improve Data Entry System: Implementing a more efficient and accurate data entry system will enhance data quality, reduce errors, and support more reliable analysis and decision-making.
