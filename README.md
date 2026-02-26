# Telecom-Churn-Analysis
Customer Churn Analysis
📌 Project Overview:
In the highly competitive telecom industry, retaining customers is more cost-effective than acquiring new ones. This Power BI Dashboard provides a deep dive into customer behavior to identify patterns leading to churn. By visualizing risk factors, the business can proactively implement retention strategies to reduce revenue loss.
🛠️ Technology Stack:
Business Intelligence: Power BI DesktopData Modeling: Power Query & DAX (Data Analysis Expressions)Key Metrics: Churn Rate, Average Tenure, Revenue Loss, and Customer Lifetime Value (CLV).

📊 Problem Statement:
The telecom company is facing a significant "leaky bucket" problem where subscribers are leaving for competitors. The goal of this analysis is to:Identify the current churn rate and the revenue impact of lost customers.Analyze which segments (contract type, payment method, internet service) have the highest churn.Determine key drivers—such as high monthly charges or lack of tech support—that influence a customer's decision to leave.

🚀 Key Insights & FeaturesChurn Summary:
High-level KPIs showing Total Customers, Churn Rate %, and Total Revenue Lost.Demographic Analysis: Breakdown of churn by gender, age group (Senior Citizens), and partner status.Contract Deep-Dive: Insights revealing that Month-to-Month contract holders are at the highest risk.Service Impact: Analysis showing how "Fiber Optic" users and those without "Online Security" are more likely to churn.Predictive Indicators: Visualizations highlighting the "Danger Zone" (e.g., customers with less than 6 months tenure).📸 Dashboard PreviewTip: Upload your .png or .jpg screenshot to your GitHub repository and update the link below.![Telecom Churn Dashboard](images/churn_dashboard_preview.png)📝 Measures Used (DAX Highlights)To provide accurate results, I created several custom measures, including:Churn Rate: $$\text{Churn Rate} = \frac{\text{Count of Churned Customers}}{\text{Total Customers}}$$Revenue at Risk: The total monthly charges of customers identified as "Highly Likely" to churn.
