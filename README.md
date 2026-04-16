Project Overview:
## Data Processing Workflow
Data was initially extracted and structured using SQL, including joins and aggregations across multiple tables. 
Python (Pandas) was then used to clean and validate the dataset by:
- Standardizing column names and formats
- Resolving duplicate columns created during joins (e.g., region fields)
- Handling missing values and removing duplicates
- Verifying calculated revenue using quantity and unit price

Objectives:	Understand revenue trends over time,Identify top-performing customers, Analyze revenue contribution by product category, Evaluate whether revenue growth is driven by order volume or AOV.

The cleaned dataset was used for exploratory analysis and then visualized in Power BI to identify trends in revenue, customer behavior, and product performance.This project analyzes sales performance using SQL and Power BI to uncover trends in revenue, customer behavior, and product category performance.

Tools Used: SQL (data extraction, joins, aggregations), Python – Pandas (data cleaning, validation, exploratory analysis), Power BI (dashboard development, visualization)

Key Metrics: Total Revenue,Total Orders, Average Order Value (AOV).
Key Insights: Revenue growth is primarily driven by increased order volume rather than AOV, Home Office category generates the highest revenue, Revenue is moderately concentrated among top customers, with higher contributors generating more revenue than the average customer, indicating some level of customer dependency.
Revenue trends show fluctuations across months, indicating potential seasonality.

Dashboard Features:KPI cards for quick performance overview, Revenue trend analysis over time, Top 10 customers by revenue, Category-level revenue breakdown, Business insight summary for stakeholders.

Python Analysis
Performed exploratory data analysis using Pandas to:
- Analyze revenue trends over time
- Identify top-performing product categories
- Evaluate customer-level revenue contribution
- Validate key metrics such as total revenue and average order value (AOV)
This step ensured data accuracy and supported insights later presented in the dashboard.
