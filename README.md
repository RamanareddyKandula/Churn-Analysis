🏦 Bank Customer Churn Analysis | Power BI
📌 Project Objective

The primary goal of this project is to identify churned bank customers, understand the key reasons behind customer churn, and deliver a reporting dashboard with meaningful insights that can help the bank reduce churn rate and improve customer retention.

🎯 Business Problem

Customer churn directly affects a bank’s revenue and long-term growth.
This project answers key business questions such as:

Which customer segments are more likely to churn?

Does churn vary by age, account balance, or credit score?

How do factors like gender, activity status, country, credit card ownership, and number of products influence churn?

📂 Data Source

Format: CSV file

Content: Bank customer demographic, financial, and behavioral data

Tool Used for Ingestion: Power BI → Power Query (Transform Data)

🛠 Tools & Technologies Used

Power BI

Power Query

DAX (Data Analysis Expressions)

CSV Dataset

🔄 Step-by-Step Project Workflow
1️⃣ Understanding the Source Data

Reviewed the CSV dataset to understand:

Customer demographics

Account and credit-related attributes

Churn indicator

Identified columns relevant for churn analysis

2️⃣ Data Collection

Imported the CSV file directly into Power BI

Opened Transform Data to begin preprocessing in Power Query

3️⃣ Data Preparation (Power Query)

Performed the following transformations:

Removed duplicate records

Removed unnecessary and irrelevant columns

Corrected data types for numerical and categorical fields

Created derived columns:

Age Groups

Account Balance Groups

Credit Score Groups

4️⃣ Reference Tables Creation

To enable focused analysis, created separate reference tables for:

Age Group Analysis

Account Balance Group Analysis

Credit Score Group Analysis

For each reference table:

Kept only required columns

Removed all unrelated columns

Created Index columns:

Age Group Index

Account Balance Group Index

Credit Score Group Index
(Used for correct sorting in area charts)

5️⃣ Data Modeling

Loaded cleaned tables into the Power BI data model

Reviewed and validated table relationships using Model View

Ensured relationships supported accurate analysis and visualization

6️⃣ Data Analysis Using DAX

Created key DAX measures for churn analysis:

Total Customers

Churned Customers

Churn Rate (%)

These measures were used consistently across all visuals.

7️⃣ Data Visualization

Built an interactive reporting dashboard using:

📈 Area Charts

Churned customers by Age Group

Churned customers by Account Balance Group

Churned customers by Credit Score Group

🍩 Donut Charts

Churn analysis by:

Gender

Active vs Inactive Status

Credit Card Status

Country

Number of Products

8️⃣ Reporting Dashboard & Insights

The final dashboard provides:

Clear visualization of churn patterns

Identification of high-risk customer segments

Easy comparison of churn across multiple customer attributes

🔍 Key Insights

Certain age groups show significantly higher churn

Customers in specific account balance ranges are more likely to churn

Lower credit score groups have higher churn rates

Inactive customers churn more than active customers

Customers with fewer products show higher churn behavior

Churn varies across countries and customer profiles

✅ Business Recommendations

Improve engagement strategies for inactive customers

Offer personalized financial products for high-risk age groups

Introduce loyalty programs for customers with fewer products

Use credit score-based offers to reduce churn

Apply region-specific retention strategies
