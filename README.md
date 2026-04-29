# Customer Segmentation & Revenue Analytics (ELT Pipeline)
End-to-end ELT data analysis project using Python to explore customer behavior and business performance. This project analyzes transactional data to segment customers, identify high-value cohorts, and quantify their contribution to revenue. It also investigates key drivers of revenue growth, including purchase patterns and customer retention, and evaluates how delivery performance (on-time vs delayed orders) impacts repeat purchases.

Key components include data cleaning and transformation, customer segmentation (high-value vs regular, repeat vs one-time), revenue and order contribution analysis, and delivery delay impact assessment. The project demonstrates practical use of pandas for data manipulation, cohort-style analysis, and business-focused metric development such as customer value and retention indicators.


📌 Project Overview

This project analyzes a Brazilian e-commerce dataset to uncover insights into customer behavior, retention patterns, and revenue drivers.
The goal is to design an end-to-end ELT data pipeline that transforms raw transactional data into actionable business insights.

📌 Business Objectives

Understand customer purchasing behavior

Identify high-value customers

Analyze drivers of revenue growth

Evaluate how delivery performance impacts repeat purchases

Measure customer retention over time

📌 Project Architecture (ELT)

    1. Extract
        Load raw CSV datasets into Python (Pandas DataFrames)
    2. Load
        Store raw and intermediate data into structured tables 
    3. Transform
        Perform cleaning, feature engineering, and aggregation using Python and visualize insights using Tableau
        
📌 Key Analysis

    1. Customer Analysis
        🔹 Customer Segmentation
            - Revenue contribution by customer segmentation
                - High Value (Top 10% by revenue)
                - Regular
        🔹 Repeat vs One-Time Customers
                - Identified percentage split and customer distribution on returned vs one-time orders
    2. Revenue Analysis
        🔹 Monthly Revenue Trends
            - Aggregated revenue by month
            - Identified growth patterns and seasonality
        🔹 Revenue Contribution
            - Compared percentage revenue distribution between Top 10% customers vs remaining 90%
    3. Delivery Performance Analysis
        🔹 Delivery Delay 
        🔹 Impact of Delivery Delay on Retention
            - Compared repeat rates between:
                - Customers with delayed deliveries
                - Customers with on-time deliveries
    4. Geographic Analysis
        🔹 Revenue by Region
            - Identified high-performing regions
            - Customer distribution across the market
        🔹 Regional Delivery Performance
            - Highlighted regions with operational inefficiencies
📌 Insights

    1. Revenue Concentration
        A small percentage of customers (top ~10%) contribute a disproportionately large share of total revenue.
    2. Customer Retention
        Most customers do not return after their first purchase, highlighting an opportunity to improve retention strategies.
    3. Delivery Impact
        Delayed deliveries are correlated with lower repeat purchase rates, indicating logistics performance directly affects customer loyalty.
    4. Customer Behavior
        Repeat customers generate significantly higher lifetime value compared to one-time buyers.
    5. Geographic Trends
        Certain regions drive higher revenue but may also experience delivery inefficiencies.
        

<img width="900" height="500" alt="Figure_1" src="https://github.com/user-attachments/assets/f5fbc9ca-3cdd-40c3-9261-fc1df0958152" />
<img width="1000" height="500" alt="Figure_2" src="https://github.com/user-attachments/assets/8c0010d9-ccdb-4fd3-b30e-1142aa88c333" />
<img width="640" height="480" alt="Figure_4" src="https://github.com/user-attachments/assets/ab54ba7e-7ad8-4a7f-9790-53fe3f1a3c12" />
