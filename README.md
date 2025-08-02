# 📊 Customer Churn Analysis – Telecom Industry

Analyze customer behavior to discover why they leave and how to retain them.

---

## 📁 Project Overview

This project explores customer churn using a structured telecom dataset. The key goals are to:

- Identify key churn drivers  
- Understand usage and service patterns  
- Generate actionable recommendations  

---

## 🛠️ Tools & Technologies

- Python (Pandas, NumPy)  
- Matplotlib, Seaborn  
- Jupyter Notebook  
- Git & GitHub for version control  

---

## 📊 Dataset Summary

The dataset contains customer-level information such as:

- `gender`: Customer gender  
- `SeniorCitizen`: 1 if senior citizen, 0 otherwise  
- `tenure`: Months with the company  
- `Contract`: Monthly/Yearly  
- `TotalCharges`: Total charges incurred  
- `Churn`: Yes (left), No (active)  
- Plus: Internet, Security, Tech Support services, etc.

---

## 🔧 Data Preprocessing

- Replaced blanks in `TotalCharges` and converted to float  
- Converted `SeniorCitizen` from binary to "Yes"/"No"  
- Verified no duplicate `customerID`  
- Ensured correct data types for all columns  

---

## 📉 Churn Analysis Summary

- **Churn Rate**: ~26.5% of customers have churned

### 🔍 Demographics:
- No churn difference by gender  
- Senior citizens churn significantly more  

### 🕒 Tenure:
- Most churn happens within the first 1–2 months  

### 📃 Contract Type:
- Month-to-month plans have the highest churn  
- Annual contracts improve retention  

### 🛎️ Services Impact:
- Lack of OnlineSecurity & TechSupport increases churn  
- Fiber optic users churn more than DSL users  

---

## 📊 Visual Insights

- ✅ Pie chart & bar plot for overall churn rate  
- ✅ Stacked bar chart: churn by senior citizen  
- ✅ Count plots for all service-related variables  
- ✅ Line/bar plots for tenure & contract trends  

---

## 🧠 Key Takeaways

- 📉 New users (low tenure) are most likely to churn  
- 👴 Senior citizens are more at risk  
- 🛡️ Customers without security/support services churn more  
- 📅 Long-term contracts help reduce churn  
- 🧪 Fiber optic services need deeper review  

---

## 💡 Recommendations

- Improve onboarding experience for new customers  
- Target senior citizens with retention offers  
- Promote annual plans with discounts  
- Upsell OnlineSecurity & TechSupport  
- Investigate Fiber service quality/pricing issues  

---

## 📂 Files in This Repository

- `Churn_Analysis.ipynb`: Jupyter notebook with full analysis  
- `Executive_Summary.pdf`: Final summary report  
- `churn_data.csv`: Dataset (if allowed)  
- `README.md`: Project overview  

---

## 👨‍💻 Author

**Shubham Pandey**  
📧 shubhampandey7064@gmail.com  
🌐 [GitHub Profile](https://github.com/Shubhampandey1808)
