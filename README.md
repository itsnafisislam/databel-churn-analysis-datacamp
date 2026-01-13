📖 Project Overview

This project analyzes a dataset from Databel, a fictional telecom provider, to identify the key drivers of customer churn. The goal is to reduce the current 26.86% churn rate by understanding why customers are leaving and which demographics or regions are most at risk.

The analysis was performed entirely in Excel, utilizing Pivot Tables, interactive Dashboards, and Data Visualization techniques.

Note: The dataset for this case study was provided by DataCamp as part of their data analytics training curriculum.

The analysis was performed entirely in Excel, utilizing Pivot Tables, interactive Dashboards, and Data Visualization techniques.
Link for the original dataset provided by DataCamp: https://assets.datacamp.com/production/repositories/6386/datasets/1c551590530839ec06bdc30a1c346920cfc9b7f3/Case%20Study_%20Analyzing%20Customer%20Churn%20in%20Excel%20(1).pdf

📂 Data Structure

The analysis is based on a dataset of 6,687 customers. The project file consists of the following key components:

Databel - Customer: The raw dataset containing row-level customer information (Demographics, Plan details, Usage, Churn status).


<img width="1195" height="699" alt="dashboard_screenshot" src="https://github.com/user-attachments/assets/d36983d9-cb2a-4cca-a66a-c3da3157085c" />

Overview (Dashboard): Summarizing the main KPIs:

Total Customers: 6,687

Churned Customers: 1,796

Churn Rate: 26.86%

Geographic Analysis: A state-level breakdown identifying high-risk areas (e.g., CA with ~63% churn).

Churn Analysis / Customer Pivots: Backend sheets containing pivot tables that drive the dashboard visualizations, focusing on reasons for churn and competitor analysis.

🔍 Key Insights & Findings

1. Top Reasons for Churn: 
The primary driver for customers leaving is Competitor Activity.

Competitor made better offer: The #1 reason for churn.

Competitor had better devices: The #2 reason for churn.

Attitude of support person: A significant internal driver for customer dissatisfaction.

2. Demographic Vulnerability: 
Seniors: This age group exhibits a significantly higher churn rate compared to other age brackets.

Under 30: Moderate churn rate, but volume is significant.

3. Geographic Anomalies: 
California (CA): Identified as a critical outlier with a churn rate exceeding 60%, significantly higher than the national average.

Other High-Risk States: IN (Indiana), NH (New Hampshire), and PA (Pennsylvania) also show concerning churn trends (>30%).

4. Consumption & Plan Patterns: 
Unlimited Data Plans: Analysis of whether customers on unlimited plans churn less frequently.

International Activity: Customers with International Plans but low actual international usage were identified as potential churn risks due to paying for unnecessary services.

🛠 Tools & Techniques Used

Microsoft Excel

Data Cleaning: Handling null values and standardizing columns.

Pivot Tables: Aggregating data for demographics and churn reasons.

Formulas: Calculated fields for Churn Rate % and Age Grouping.

Conditional Formatting: "Heat map" visualizations to highlight high-churn states.

Dashboarding: KPI and Charts (Bar, Donut, Line).

Here is the project file structure:


🚀 Recommendations

Based on the analysis, the following actions are recommended:

Competitive Pricing Strategy: Launch a targeted retention offer to counter competitor pricing, specifically for customers identified as "price-sensitive."

Senior Support Program: Simplify the customer journey and offering for the Senior demographic to reduce their specific churn rate.


California Investigation: Conduct a localized audit in CA to determine if there is a specific network outage or aggressive local competitor causing the >60% churn.

