Relix Sales Data Analysis *
An Exploratory Data Analysis (EDA) project focused on uncovering purchasing patterns and customer demographics for Relix. This project uses Python to clean raw sales data and visualize key performance indicators (KPIs) to drive business decisions.
* Project Overview
The objective of this analysis is to identify the target customer segment by analyzing variables such as Gender, Age, Geography, Occupation, and Product Categories.

* Tech Stack
Language: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn
Environment: Jupyter Notebook (.ipynb)

* Data Cleaning Highlights
Before analysis, the dataset underwent several preprocessing steps:
Handling Nulls: Identified and removed 12 empty rows in the Amount column to ensure accuracy.
Data Type Conversion: Converted Amount from float to int64 for cleaner calculations.
Feature Engineering: Dropped unnecessary/blank columns (Status, unnamed1).
Validation: Used .describe() to perform a statistical audit of Age, Orders, and Amount.

* Key Insights from EDA
1. Gender & Purchasing Power
Finding: Females significantly outnumber males in both transaction count and total spending.
Visualization: Countplots and Barplots confirm that the purchasing power of women is substantially higher.
2. Age Demographics
Finding: The 26-35 year old age group is the most active.
Trend: Within this age bracket, females contribute the most to the total revenue.
3. Geographic Performance
Finding: Uttar Pradesh, Maharashtra, and Karnataka are the top three performing states.
Note: Uttar Pradesh leads in both the number of orders and total sales value.
4. Occupation & Marital Status
Finding: Most buyers are Single Women working in the IT, Healthcare, and Aviation sectors.
5. Product Preferences
Finding: While Clothing has the highest volume of orders, the Food category generates the highest total revenue.

* Conclusion
The data suggests that the ideal customer profile for Relix is a single woman aged 26-35 residing in Uttar Pradesh or Maharashtra, employed in the IT or Healthcare sectors. Marketing efforts should prioritize Food and Clothing categories to maximize ROI.
