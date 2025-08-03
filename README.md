# FUTURE_ML_02
# 📊 Customer Churn Prediction System
Internship Task 2 – AI-Powered Churn Prediction Dashboard

#FutureInterns #PowerBI #ChurnPrediction #MachineLearning #CustomerAnalytics

# 🔍 Objective
The goal of this project is to develop a Churn Prediction System using Machine Learning models and visualize the churn insights using Power BI Dashboard. 

This project helps identify customers at high risk of leaving (churning), which is crucial in sectors like telecom, banking, and SaaS, where retention is more cost-effective than acquisition.

# 📁 Files Included

+ File/Notebook	Description
- Customer_Churn_Prediction.ipynb	Google Colab notebook with full preprocessing, ML model, and predictions
- WA_Fn-UseC_-Telco-Customer-Churn.csv	Original Telco customer churn dataset
- churn_predictions.csv	Dataset with new columns like Churn_Probability, High_Risk
- Churn_Prediction_Dashboard.pbix	Power BI dashboard file showing insights and churn analytics

# 📦 Datasets Used

- WA_Fn-UseC_-Telco-Customer-Churn.csv: &nbsp;&nbsp;  Contains 7000+ customer records with demographic, billing, and churn-related data.
- churn_predictions.csv:  &nbsp;&nbsp; Includes additional columns after model prediction:
- Churn_Probability: &nbsp;&nbsp; Probability of churn (0 to 1)
- High_Risk: &nbsp;&nbsp; "Yes" if probability > 0.7, otherwise "No"

# 🤖 Google Colab Notebook
- The notebook performs:
- Data Cleaning and Preprocessing
- Label Encoding and Feature Engineering
- ML Model Training (e.g., Random Forest, Logistic Regression)
- Prediction of Churn_Probability
- Derivation of High_Risk column
- Output saved as churn_predictions.csv for Power BI


# 📈 Power BI Dashboard Details

* 🔵 Key KPIs
- Count of Monthly Charges –&nbsp; Total monthly charges across all customers
- Count of Customers –  &nbsp;Total number of customers
- Count of Tenure – &nbsp;Cumulative tenure of all customers
- Sum of Total Charges –&nbsp; Overall revenue generated
- Sum of Senior Citizens – &nbsp;Total senior citizens in dataset

# 🟣 Visual Insights
1. Churn Distribution Card
   - Binary cards showing “Yes” vs “No” churned customers
2. High-Risk Customers Pie Chart
   - High_Risk (Yes/No) distribution
   - Helps identify customers with churn probability > 0.7
   Example: 14% of customers are high risk (1015 customers)
3. Churn Probability by Gender Donut Chart
   - Shows how churn probability is distributed across genders
4. Churn by Internet Service Stacked Bar Chart
   - Helps identify churn rate by service types (Fiber optic has high churn)
5. Churn by Tenure Line Chart
   - Customers with very low or very high tenure are most likely to churn
6. Total Charges vs Tenure by Churn Line Area Chart
   - Shows revenue generated over customer tenure and whether they churned or not
7. Payment Method Checkbox Slicer
   - Allows filtering of churn based on payment methods

<img width="1216" height="678" alt="image" src="https://github.com/user-attachments/assets/1252a3ab-001c-4b39-a4c4-5de7da6b6f24" />


+ 📊 High Risk Customers Meaning
> High_Risk = "Yes" if the customer's Churn_Probability > 0.7
> This allows businesses to target retention efforts on these specific customers.

✅ Used for pie chart to show how many customers are at high risk.

# 🙏 Acknowledgment

This project was done as part of my internship at #FutureInterns under Task 2:

"Churn Prediction System using Machine Learning and Power BI".

Thanks to the mentors and team for the opportunity and guidance throughout this learning journey.

# Linked in 
 https://www.linkedin.com/in/dhanusha-katakam-ediga-3756ab341/
 
#FutureInterns #PowerBI #ChurnPrediction #Dashboard #MachineLearning #DataScience #InternshipProject
