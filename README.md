# Orders-Data-Analysis
This project focuses on the analysis of orders data obtained from the Kaggle API. The objective is to derive insights regarding product revenue, sales performance across regions, month-over-month growth, and category performance. The cleaned DataFrame was then uploaded to a Microsoft SQL Server database for further analysis and querying.

# Data Cleaning
Before performing the analysis, the dataset underwent several cleaning steps:

1. ** Handling Null Values:
    -Identified and filled or removed null values in critical columns to ensure data integrity.

2. ** Creating New Columns:
    -New calculated columns were created, such as total_revenue (calculated as quantity * sale_price) and profit_margin (calculated as profit / total_revenue).

3. ** Deleting Irrelevant Columns:
-Removed columns that did not contribute to the analysis, ensuring the dataset remained focused and manageable.

# Conclusion
The analysis of the orders data provided valuable insights into product performance, regional sales trends, and growth comparisons. This project highlights the importance of data cleaning and structured querying in deriving actionable business intelligence from raw data.

# References
Kaggle API for dataset acquisition.
Microsoft SQL Server for data storage and querying.
Pandas and PyODBC for data manipulation and database interaction in Python.
