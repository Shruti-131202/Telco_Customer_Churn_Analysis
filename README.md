# Telco_Customer_Churn_Analysis
This project involves a detailed Churn Analysis and Prediction Dashboard built using Power BI and powered by a machine learning model for customer churn prediction. The dashboard visualizes the behavior and characteristics of churned customers to help businesses reduce attrition and improve customer retention.
## Dataset
<a href= "https://github.com/Shruti-131202/Telco_Customer_Churn_Analysis/blob/main/telco.xlsx"> Telco.csv</a>
 ## Key figures:
- Total Customers: 2003
- Predicted Churners: 447
- Churn Rate: 41%
- Model Used: Logistic Regression (for classification of churn likelihood)

## Process
- Data Cleaning & Preprocessing
- Handled missing values, encoded categorical data.
- Created tenure groups, charge ranges, and churn reason mapping.
## Churn Prediction Model
- <a href="https://github.com/Shruti-131202/Telco_Customer_Churn_Analysis/blob/main/Telco_Churn_prediction.ipynb">Logistic Regression model</a>
- Used Python to train a Logistic Regression model.
- Features used: contract type, payment method, tenure, total charges, internet type, etc.
- Output: Binary prediction – Churn or Not Churn.
## Dashboard Creation in Power BI
- <a href="https://github.com/Shruti-131202/Telco_Customer_Churn_Analysis/blob/main/Churn_Summary.jpg">Churn Summary</a>
- <a href="">Churn prediction</a>
-Integrated predicted churn results with customer profiles.
- Built visual summaries based on:
- Gender, Age Group, Contract Type
- City-wise Churn Rates
- Payment Method impact
- Churn Reason Distribution
- Internet Type and Tenure Trends

## Insights & Conclusion
- Majority of churners are under Month-to-Month contracts.
- Customers paying via Mailed Check or Credit Card show higher churn.
- Cities like Los Angeles and San Diego have the most churners.
- Low tenure and poor support are key churn drivers.
- The churn prediction model achieved solid performance in classifying customers with high churn probability, enabling proactive retention strategies.

