# Telecom Customer Churn Risk & Revenue Impact Analysis
## Business Problem
A telecom company is experiencing customer attrition, impacting recurring revenue and increasing acquisition costs. The objective of this analysis was to:
- Identify high-risk churn customers
- Understand key churn drivers
- Quantify potential revenue at risk
- Recommend targeted retention strategies
## Dataset Overview
- Total Customers: 7,043
- Predicted High-Risk Customers: 447
- Overall Churn Rate: 27%
- Features: Contract type, tenure, internet service, payment method, monthly charges, churn reason, etc.
- Machine Learning Model: Random Forest Classifier (Python)
## Key Business Metrics
- 447 customers flagged as high churn risk
- ₹52,492 total revenue from predicted churners
- Month-to-Month contracts show 46% churn rate (highest risk segment)
- Fiber Optic users show 41% churn rate
- Mailed Check users show 37% churn rate
## Major Churn Drivers (Descending Order)
- Churn reasons ranked by frequency:
- Service dissatisfaction
- Product dissatisfaction
- Price too high
- Poor phone support expertise
- Poor online support expertise
- Network reliability issues
- Relocation (moved)
This indicates that operational and service quality issues drive majority of churn rather than demographic factors.
## High-Risk Segments Identified
- Month-to-Month + Fiber Optic users
- Customers with tenure < 12 months
- Mailed Check payment users
- High monthly charge customers (> median range)
- These segments show significantly higher churn probability compared to long-term contract users.
## Revenue at Risk Analysis
- Total revenue from predicted churners: ₹52,492
- If even 30% of high-risk customers are retained through targeted interventions:
- Projected revenue saved ≈ ₹15,747
- This excludes long-term lifetime value impact.
## Business Recommendations
- Convert Month-to-Month customers to 1-year contracts via discount incentives
- Improve service quality in top churn categories (service & product dissatisfaction)
- Incentivize Auto-Pay adoption to reduce churn probability
- Target first-year customers with proactive retention campaigns
- Launch customer experience improvement program for Fiber Optic segment
- Projected churn reduction: 8–12% with structured retention strategy.
## Tools & Tech Stack
- Python 
- Random Forest Classifier
- Power BI Dashboard
- SQL for data validation
