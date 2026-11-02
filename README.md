# DecodeLabs-Exploratory-Data-Analysis-Project-2
An Exploratory Data Analysis project using Excel and PowerBi to examine sales performance, customer activity, order statuses, payment methods, trends and potential outliers..

# Project Overview
This project focuses on Exploratory Data Analysis (EDA) using a sales and order dataset containing 1,200 records.
The objective was to explore the dataset, understand sales patterns, examine customer activity, identify trends and potential outliers, and communicate the findings through a Power BI dashboard.

# Tools Used
* Microsoft Excel: Data cleaning, data exploration, descriptive statistics, PivotTables and outlier analysis.
* Power BI: Data visualisation and dashboard development.

# Project Objectives
* Clean and prepare the dataset for analysis.
* Calculate basic descriptive statistics.
* Examine sales performance across products.
* Analyse monthly sales trends.
* Explore order status and payment method distributions.
* Identify top customers by recorded sales value.
* Detect potential outliers using the IQR method.
* Present key findings through a dashboard.

## Data Cleaning
The dataset was reviewed and prepared in Excel before analysis. Some of the cleaning activities included:
* Checking for missing values.
* Replacing blank Coupon Code entries with "No Coupon Used".
* Reviewing repeated Customer IDs.
* Checking data consistency and formatting.
* Preparing the cleaned dataset for analysis.
The dataset contained 1,200 order records and 1,189 unique customers. Eleven customers appeared twice. These records were retained because repeated Customer IDs do not automatically indicate duplicate orders.

## Exploratory Data Analysis
# 1. General Sales Overview
 Metric                            Result 
 Total Orders                        1,200 
 Unique Customers                    1,189 
 Total Recorded Sales Value  $1,264,761.96 
 Average Order Value             $1,053.97 
 Median Order Value                $823.62 | Highest Order Value   $3,456.40 
 Lowest Order Value                $11.39 
 Average Quantity per Order           2.95 
Average Unit Price                $356.41 

# 2. Product Analysis
Seven products were analysed.
* Chair recorded the highest sales value at $195,620.11.
* Phone recorded the lowest sales value at $151,722.39.

# 3. Monthly Sales Trend
The yearly recorded sales values were:
 Year         Recorded Sales Value 
 2023         $552,643.24 
 2024         $480,235.87 
 2025          $231,882.85 
The monthly figures showed fluctuations rather than a consistent upward or downward pattern. The 2025 figures cover January to June only.

# 4. Order Status Analysis
 Cancelled: 250 orders
 Returned: 247 orders
 Pending: 237 orders
 Shipped: 235 orders
 Delivered: 231 orders
Cancelled and returned orders accounted for 497 records, approximately 41.4% of all orders.

# 5. Payment Method Analysis
 Online: 258 orders
 Cash: 246 orders
 Credit Card: 234 orders
 Debit Card: 232 orders
 Gift Card: 230 orders
Online payments had the highest number of orders, while Gift Card payments had the lowest.

# 6. Customer Analysis
The analysis identified 1,189 unique customers across 1,200 order records.
A Top 10 customer analysis was also performed in Power BI. Customer ID C38840 ranked highest, with a combined recorded order value of $5,723.23 across two orders.

# 7. Outlier Analysis
The Interquartile Range (IQR) method was used to identify potential outliers.
 Metric                Value 
 Q1                 $410.52 
 Q3               $1,578.475 
 IQR              $1,167.955 
 Lower Bound    -$1,341.4125 
 Upper Bound     $3,330.4075 
 High Outliers             8 
 Low Outliers              0 
Eight potential high outliers were identified. These records were flagged for review rather than automatically removed.

# Power BI Dashboard
The Power BI dashboard presents the main findings through:
* KPI cards
* Recorded Sales Value by Product
* Monthly Sales Trend
* Order Distribution by Status
* Order Distribution by Payment Method
* Top 10 Customers by Sales

# Key Learnings
Working on this project gave me practical experience in:
* Cleaning and preparing data using Excel.
* Using descriptive statistics to understand a dataset.
* Creating PivotTables to explore different categories.
* Identifying trends and potential outliers.
* Building visual reports in Power BI.
* Communicating findings based on data.

## Conclusion
This project strengthened my understanding of the EDA process and showed me how Excel and Power BI can be used together to explore data, identify patterns and present findings clearly.

