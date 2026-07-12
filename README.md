**Superstore Sales Dashboard — Power BI**

**Overview**
An end-to-end interactive sales dashboard built on the
Kaggle Superstore Sales dataset (9,800+ rows).
Built entirely from scratch as my first Power BI project.

**Tools Used**
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query

**What I Did**

**Data Cleaning (Power Query)**
- Fixed data types — Sales to decimal, dates to date format
- Changed Postal Code to text to preserve leading zeros
- Extracted Year, Month and Quarter from Order Date
- Trimmed whitespace from text columns
- Removed unnecessary columns

**Data Model**
- Created a Date Table using CALENDARAUTO()
- Built a one-to-many relationship between the Date Table and the Superstore Sales Dataset (fact table), on Order Date

**DAX Measures**
- Total Sales — sum of all sales
- Total Orders — count of all transactions
- Avg Order Value — sales divided by orders
- Sales Last Year — same period last year comparison using SAMEPERIODLASTYEAR
- YoY Growth % — year over year growth percentage
- Avg Shipping Days — average days from order to shipment

**Dashboard Visuals**
- KPI Cards for Total Sales, Orders and Avg Order Value
- Monthly Sales Trend line chart across 4 years
- Sales by Category bar chart
- Sales by US State map
- Top 10 Customers by Sales table (dynamic Top N filter)
- Slicers for Year, Region and Category

**Key Insights**
- Technology is the highest selling category (₹827K)
- Q4 consistently spikes every year across all years
- West region leads in total sales (₹710K)
- 2018 was the highest revenue year (₹722K)

**Files**
- Superstore_Sales.pbix
- Superstore_Sales_Dataset.csv
- dashboard_screenshot.png

**Dataset Source**
Kaggle — Superstore Sales Dataset
