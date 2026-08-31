# PhonePe-PowerBI-Analysis
Recommended Structure and Order
1. Project title / Headline :
PhonePe Data Analysis & Interactive Power BI Dashboard | Transaction Trends & Business Insights

2. Short Description / Purpose : 
This project is an interactive Power BI dashboard developed to analyze PhonePe digital payment transaction data and extract meaningful business insights.
The dashboard provides a comprehensive view of transaction performance across different states, districts, years, quarters, and transaction categories.
The project demonstrates an end-to-end data analytics workflow, including data cleaning, transformation, data modeling, DAX calculations, KPI development, and interactive data visualization.

3. Project Objective :
The primary objective of this project is to transform raw PhonePe transaction data into an interactive and easy-to-understand business intelligence dashboard.

Key objectives:
1. Analyze overall transaction performance
2. Identify transaction trends over time
3. Compare state-wise transaction activity
4. Analyze transaction categories
5. Understand geographical transaction patterns
6. Create meaningful KPIs
7. Build an interactive dashboard for business analysis
8. Generate actionable insights from transaction data

4. Tools & Technologies : 
Tool	Purpose
1.  Power BI	Dashboard & Data Visualization
2.  ower Query	Data Cleaning & Transformation
3.  AX	Measures & Calculations
4. Data Modeling	Relationships & Data Structure
5.  Excel / CSV	Data Source

5. Project Workflow : 
1.  Data Collection: The project uses PhonePe transaction data containing information related to transaction amounts, transaction counts, geographical locations, time periods, and transaction categories.

2️. Data Cleaning: The raw data was cleaned and prepared using Power Query.
The following operations were performed:
Removed unnecessary columns
Checked missing values
Removed duplicate records where required
Corrected data types
Standardized data
Prepared the dataset for analysis

3️. Data Transformation: The cleaned data was transformed into an analysis-ready format.
Important dimensions included:
Year
Quarter
State
District
Transaction Type
Transaction Category

4️. Data Modeling: A structured data model was created to establish relationships between relevant tables.
The data model was designed to support accurate calculations and dynamic filtering throughout the dashboard.

5️. DAX Calculations: DAX measures were created to calculate important business KPIs.
Example:
Total Transaction Amount =SUM(Transaction[Transaction_Amount])
Total Transactions =SUM(Transaction[Transaction_Count])
Average Transaction Value =DIVIDE(
    [Total Transaction Amount],
    [Total Transactions],
    0
)

These measures were used throughout the dashboard to provide dynamic results.

6. Dashboard Features : 
The dashboard contains multiple interactive visualizations and KPIs.
1. KPI Cards: Displays important metrics such as:
Total Transaction Amount
Total Transaction Count
Average Transaction Value

2. Transaction Trend Analysis: Analyzes transaction performance across:
Year
Quarter
Time period
3. State-wise Analysis: Provides a comparison of transaction activity across different states.

4. Transaction Category Analysis: Helps identify the contribution and popularity of different transaction categories.

5. Geographical Analysis: Provides insights into transaction activity across different geographical regions.

6. Interactive Filters: Users can dynamically filter the dashboard using:
Year
Quarter
State
Transaction Category
Transaction Type

🔍 Key Insights : 
The dashboard helps identify:

📌 States with higher transaction activity

📌 Changes in transaction volume over time

📌 Regions contributing significantly to transaction activity

📌 Popular transaction categories

📌 Quarterly transaction patterns

📌 Geographical variations in digital payment activity

These insights can help businesses understand digital payment behavior and regional transaction trends.

7. Screenshot (https://github.com/Pratistha2216/PhonePe-PowerBI-Analysis/blob/main/Snapshot%20of%20the%20Dashboard.png)
