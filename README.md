📊 Customer Churn Analysis — Telecom Dataset
🔍 Project Overview
This project focuses on understanding the key factors contributing to customer churn in a telecom company. Using Python and its powerful data analysis libraries, we explore patterns, trends, and correlations in customer behavior to generate actionable insights that can help reduce attrition and improve retention strategies.

📁 Dataset Information
The dataset used includes customer demographics, service details, account information, and churn labels.

Key Features:

gender, SeniorCitizen, Partner, Dependents

tenure, Contract, MonthlyCharges, TotalCharges

PhoneService, InternetService, OnlineSecurity, TechSupport, etc.

Churn: Target variable indicating if the customer has left.

📌 Source: Public telecom dataset (e.g., Telco Customer Churn dataset from Kaggle)

🧹 Data Preprocessing
Handled missing values (especially in TotalCharges)

Converted SeniorCitizen from binary to categorical

Removed irrelevant or empty columns if any

Casted numerical columns to appropriate types

Verified uniqueness of customerID

📊 Exploratory Data Analysis (EDA)
🔸 Churn Overview
26.5% of customers have churned

Pie chart and count plot used for visualization

🔸 Demographic Analysis
Senior citizens show a significantly higher churn rate

Gender has no strong impact on churn

🔸 Tenure & Contract Impact
Churn is highest among customers with 1–2 month tenure

Month-to-month contracts show the most churn

Yearly contracts improve customer retention

🔸 Service Usage Insights
Service Feature	Churn Insight
InternetService	Fiber optic users churn more than DSL users
OnlineSecurity	Customers without this service churn more
TechSupport	Absence linked with higher churn
StreamingTV/Movies	Lower usage among churners
DeviceProtection	No plan = higher churn likelihood
OnlineBackup	Lack of backup service linked with churn

✅ Created a subplot grid of count plots for all service categories segmented by churn status.

📌 Key Takeaways
Early churn is a major issue — new customers are most at risk

Long-term contracts reduce churn

Missing value-added services (security, support, etc.) increase churn risk

Senior citizens need targeted retention campaigns

Fiber optic service may have satisfaction or cost concerns

✅ Business Recommendations
Improve Onboarding for new and senior users

Promote Yearly Contracts through incentives

Bundle Key Services like Online Security & Tech Support

Review Fiber Optic Plans and customer feedback

🛠️ Technologies Used
Python (Pandas, NumPy, Seaborn, Matplotlib)

Jupyter Notebook

Excel/CSV (initial dataset cleaning)

GitHub (for version control and project hosting)

