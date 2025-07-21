# Telecommunication-Analysis-Project
Telecom Churn Analysis
This project explores customer churn patterns in a telecommunications company, with the goal of identifying high-risk segments and recommending business actions to reduce churn and increase retention.

Business Problem
Telecom companies often face high churn rates, especially among new customers. This analysis investigates which customer segments are most likely to churn, why they churn, and what strategic actions could be taken to prevent it.

Dataset Overview
The dataset includes:
Customer tenure (in months)
Monthly charges
Contract type (month-to-month, one-year, two-year)
Payment method & paperless billing
Churn label (Yes/No)

Key Insights
Business Question	                            Insight	                                            Recommendation
Which contract type churns most?	            Month-to-month contracts have 40%+ churn          	Offer discounts for yearly subscriptions
When are customers most likely to churn?     	First-year churn is the highest	                    Focus retention efforts in first 12 months
Do charges influence churn?	                  Customers with high charges churn more	            Customize affordable pricing tiers or offer better value explanation

Visualizations
Bar chart of churn rate by contract type
Line chart of churn rate across tenure stages
Average monthly charges by tenure segment
Annotated pie chart of tenure distribution

Recommendations for Airtel Nigeria
1. First-Year Retention:
Customers who churned within 0–12 months made up the largest churn group. Airtel can reduce this by:
Sending welcome offers with personalized data or call bundles after 30, 90, and 180 days.
Triggering exclusive 1-year anniversary bonuses (e.g., 1GB + 200 bonus airtime) to encourage continued usage.
Deploying “We value your loyalty” WhatsApp/SMS messages at months 6 and 10 offering rollover benefits or flexible top-up incentives.

2. Month-to-Month Users:
Month-to-month subscribers showed over 40% churn. Airtel can:
Launch a “Stay 3 months, Get 1 Month Free” campaign for these customers.
Present upsells through the MyAirtel App that bundle 3–6 month prepaid plans with free data or family sharing.

3. High-Charge Customers:
Customers with monthly charges above ₦7,000 had elevated churn risk.
Send them quarterly value reports showing benefits they’re receiving.
Offer a downgrade option or “SmartSave plan” before they decide to leave — reducing churn without revenue loss.

4. Contract Conversions:
Encourage 6–12 month plan commitment with:
Prepaid data-only contracts for students or remote workers with 10% bonus every renewal.
Family bundle contracts with multi-line discounts + bonus data for parents with teens.

5. Billing & Payment Optimization:
Manual payers (e.g., cash or bank transfers) churned more than automatic payers.
Introduce a ₦100 monthly airtime bonus for 3 months for customers who switch to auto-renewal or bank card linking.
Add airtime-based loyalty points on recurring auto-billing.

6. Targeted Churn Prevention:
Electronic check or similar manual payers churned faster.
Use SMS to send early churn-risk alerts: “You’ve been with us 10 months — we’d love to reward you. Tap here.”
Create AI-triggered retention messages on low usage, top-up delays, or app inactivity.

Tools Used
Python (Pandas, Seaborn, Matplotlib)
Jupyter notebook
Exploratory Data Analysis
Grouping, segmentation, visualization
Business storytelling

Project Structure
telecom_churn_analysis.ipynb — Full analysis notebook
telco dataset
README.md — This file

Future Projrct
Build churn prediction model using logistic regression or random forest
Add customer lifetime value (CLV) calculations
Deploy as an interactive dashboard (Streamlit or Power BI)


