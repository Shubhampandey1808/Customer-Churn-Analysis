📊 Customer Churn Analysis – Telecom Industry
Analyze churn behavior to discover why customers leave and how to retain them.

📁 Project Overview
This project explores customer churn using a structured telecom dataset. The aim is to:

Identify key churn drivers

Understand usage and service patterns

Generate actionable recommendations

🛠 Built using Python, Pandas, Matplotlib, and Seaborn.

📊 Dataset Summary
The dataset contains customer-level information:

Column Name	Description
gender	Customer gender
SeniorCitizen	1 if senior citizen, else 0
tenure	Months with the company
Contract	Type of contract (Monthly/Yearly)
TotalCharges	Total charges incurred
Churn	Target column: Yes (left), No (active)
...	Includes service features like Internet, Security, etc.

🔧 Data Preprocessing
Replaced blanks in TotalCharges and converted to float

Converted SeniorCitizen from binary to "Yes"/"No"

Verified no duplicate customerID

Ensured correct data types for all columns

📉 Churn Analysis Summary
Churn Rate: ~26.5% of customers have churned

Demographics:

No churn difference by gender

Senior citizens churn significantly more

Tenure:

Most churn happens in the first 1–2 months

Contract Type:

Month-to-month plans have the highest churn

Annual contracts increase retention

Services Impact:

Lack of value-added services (OnlineSecurity, TechSupport) increases churn

Fiber optic users churn more than DSL customers

📊 Visual Insights
✅ Pie chart & bar plot for overall churn rate

✅ Stacked percentage bar chart for churn by senior citizen

✅ Count plots for all service-related variables

✅ Tenure and contract trends shown via bar/line plots

✅ Key Takeaways
📉 New users (low tenure) are most likely to churn

👴 Senior citizens are more at risk

📶 Customers without OnlineSecurity or TechSupport churn more

💡 Long-term contracts greatly improve retention

🧪 Fiber optic service may need quality or pricing review

💡 Recommendations
Improve onboarding for new customers

Target senior citizens with retention offers

Promote annual contracts via discounts

Upsell value-added services like security & support

Evaluate fiber optic feedback for churn reasons

📂 Files in Repository
bash
Copy
Edit
├── Churn_Analysis.ipynb        # Full analysis notebook
├── Executive_Summary.pdf       # Final summarized PDF
├── churn_data.csv              # Dataset (if permitted)
├── README.md                   # This file
📎 Tools Used
Python (Pandas, NumPy)

Matplotlib, Seaborn

Jupyter Notebook

GitHub for version control

👨‍💻 Author
Shubham Pandey
📧 shubhampandey7064@gmail.com
🌐 GitHub
