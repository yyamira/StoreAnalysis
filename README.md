Overview
This project analyzes a dataset containing sales and operational details of various stores. It explores relationships between store area, items available, daily customer count, and total sales to identify key factors influencing revenue. The analysis is conducted using Python and various data science libraries.

Dataset
The dataset consists of 896 records with the following attributes:

Store_Area: Physical area of the store (square yards).
Items_Available: Number of different items available in the store.
Daily_Customer_Count: Average daily customer visits.
Store_Sales: Total sales revenue (USD).
Exploratory Data Analysis (EDA)
Key steps include:

Data cleaning (removal of Store ID, checking for duplicates, handling missing values)
Visualizing feature distributions and correlations
Identifying potential outliers
Correlation analysis to assess relationships between variables
Key Findings
Store area and items available show a weak correlation with sales.
Daily customer count has little impact on revenue.
Cluster analysis suggests four optimal store groupings.
Minor outliers were detected, but overall data integrity is maintained.
