# Costco Sales Analysis

This Power BI project provides insights into Costco's sales performance by analyzing revenue, profit, and quantity sold across regions and segments. It includes key metrics, year-over-year (YoY) comparisons, and interactive visuals to assist stakeholders in monitoring and optimizing business performance.

## Objective
The goal of this project is to:
- Track revenue, profit, and quantity sold across different regions and segments.
- Compare actual performance with targets.
- Visualize year-over-year (YoY) changes in revenue and profit.
- Enable interactive analysis through filters and bookmarks.

## KPIs
The following Key Performance Indicators (KPIs) were used in this analysis:
- **Revenue**: Total revenue generated from sales.
- **Profit**: Total profit after deducting costs.
- **Quantity Sold**: Total number of products sold.

## Process Overview
1. **Data Cleaning**:
   - Removed null and duplicate values.
   - Standardized column headers and ensured data types were consistent.
   - Addressed outliers in revenue, profit, and quantity columns.

2. **Data Loading**:
   - Imported raw data into Power BI using Excel and Power Query.
   - Structured data into fact and dimension tables for easier modeling.

3. **Data Modeling**:
   - Created a **Date Table** for time-based calculations.
   - Built relationships between fact tables and dimension tables (e.g., Products, Regions).

**Measure Table**:
   - Developed custom DAX measures for key metrics:
     - **Total Sales**: `SUM(Sales[Sales Amount])`
     - **Total Revenue**: `SUM(Sales[Revenue])`
     - **Total Quantity Sold**: `SUM(Sales[Quantity])`
 	-**Profit**: `SUM(Sales[Profit])`
     - **YoY Revenue**: `CALCULATE([Total Revenue], SAMEPERIODLASTYEAR(Dates[Date]))`
     - **YoY Profit**: `CALCULATE([Profit], SAMEPERIODLASTYEAR(Dates[Date]))`
**Interactive Features**:
   - Added **Filter Pane** to enable users to filter data by regions, products, and time.
   - Used **Bookmarks** for navigation between different report pages.
### 1. **Overview**
- **Clustered Bar Chart**:
  - Visualizing **Total Revenue** and **Total Profit by Region**.
- **Gauge Chart**:
  - Comparing **Orders vs Target Orders**.

### 2. **Segment Analysis**
- **Doughnut Chart**:
  - Showing **Revenue by Segment**.
- **Map Visual**:
  - Displaying **Total Revenue by Region**.

### 3. **Performance Over Time**
- **Line Chart**:
  - Tracking **Revenue Target vs Total Revenue** over time.

## Filters and Navigation
- **Filter Pane**:
  - Includes filters for regions, products, and time ranges.
- **Bookmarks**:
  - Allows quick navigation between pages (e.g., Overview, Segment Analysis, Performance).

## Technologies/Tools Used
- Power BI Desktop
- Power Query for data transformation
- DAX for creating calculated measures

## Conclusions
sales and profit in 2020 was down due to Covid pandemic 
State of California has highest Revenue and profit of all the states
Orders target was missed in all the 5 year period by a small margin
Profit margin is shown in the table with conditional formatting
