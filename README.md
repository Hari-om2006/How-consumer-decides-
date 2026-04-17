# How-consumer-decides-
Customer Shopping Behavior Analysis using 3,900 transactions to uncover patterns and insights. Data is cleaned with Python, analyzed using SQL (PostgreSQL), and visualized in Power BI. Focuses on customer segmentation, product performance, and discount impact for better business decisions.


Tech used:- 
Data Cleaning & Preprocessing: Python (Pandas, NumPy) 
Database Management: PostgreSQL Data Integration: SQLAlchemy (Python-to-SQL bridge) 
Analysis: SQL (Analytical querying) 
Visualization: Power BI 

WorkflowData:- 
Loaded raw CSV data, handled missing values in review ratings, and standardized column names to snake_case.Feature Engineering: Created new attributes such as age_group (via quantile-based binning) and converted categorical purchase frequencies into numeric values.
Database Integration: Transferred the cleaned dataset into a PostgreSQL database named customer_behaviour for efficient structured querying.
SQL Analysis: Executed complex queries to analyze revenue by gender, high-spending discount users, and product performance.
Visualization: Developed an interactive Power BI dashboard to present key findings visually.
