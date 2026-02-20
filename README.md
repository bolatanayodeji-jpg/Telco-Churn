# Telco-Churn
Telco churn Dashboard

📊 Telco Customer Churn Analysis & Prediction
🔎 Project Overview

Customer churn is a major challenge in the telecommunications industry, where competition is high and customer retention costs significantly exceed acquisition costs.

This project analyses customer churn patterns using structured telecom data and builds predictive insights to support customer retention strategies. The analysis was visualised using Power BI to create an interactive decision-support dashboard.

Dataset Source: Kaggle Telco Customer Churn Dataset (7,043 customers, 21 features)

🎯 Business Problem

The objective was to:

Identify key drivers of customer churn

Analyse customer behaviour across contract types and tenure

Understand the impact of pricing and service usage

Provide data-driven recommendations to reduce churn

Telecom companies risk profitability when high-value customers leave. Predicting churn enables proactive intervention.

🛠 Tools & Technologies Used

Power BI

DAX

Power Query

Excel

Data Cleaning & Transformation

Exploratory Data Analysis (EDA)

📂 Dataset Description

The dataset contains:

7,043 customer records

21 variables including:

Demographics (gender, senior citizen, partner, dependents)

Contract type

Monthly charges

Tenure

Internet service

Payment method

Churn (Yes/No)

📈 Key KPIs Analysed

Overall Churn Rate

Churn by Contract Type

Churn by Tenure Group

Churn by Monthly Charges

Churn by Internet Service Type

Customer Lifetime Value Indicators

📊 Dashboard Insights
1️⃣ Contract Type & Churn

Month-to-month contracts had the highest churn rate

Long-term contracts significantly reduced churn

📌 Insight: Encourage contract upgrades to reduce attrition.

2️⃣ Tenure Analysis

Customers with shorter tenure were more likely to churn

Long-standing customers showed higher retention

📌 Insight: Early engagement strategies are critical.

3️⃣ Monthly Charges Impact

Higher monthly charges correlated with increased churn probability

📌 Insight: Price sensitivity plays a major role in churn behaviour.

4️⃣ Service Usage Patterns

Customers using Fibre Optic internet showed higher churn rates

📌 Insight: Service quality or pricing structure may need review.

📌 Example DAX Measure
Churn Rate % = 
DIVIDE(
    CALCULATE(COUNT(Telco[Churn]), Telco[Churn] = "Yes"),
    COUNT(Telco[CustomerID])
) * 100

💡 Business Recommendations

Promote long-term contracts with targeted incentives

Focus retention campaigns on new customers (0–12 months tenure)

Offer personalised pricing plans for high-charge customers

Improve service quality for high-risk segments

🚀 Skills Demonstrated

Business Intelligence Reporting

KPI Development

Customer Behaviour Analysis

Predictive Thinking

Dashboard Design

Data Storytelling

Analytical Problem Solving

📁 Repository Contents

Power BI Dashboard (.pbix file)

Dataset 

Dashboard Screenshots

README Documentation
