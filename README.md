🚨 Churn Prediction System

Python | Scikit-learn | XGBoost | Matplotlib

🔍 Project Overview

This project focuses on building a machine learning–based churn prediction system that identifies customers who are likely to stop using a service.

Using the Telco Customer Churn Dataset, classification models were trained to predict customer churn and analyze the key factors influencing customer attrition. The project emphasizes model evaluation, feature importance, and business insights derived from the predictions.

🎯 Business Problem

Customer churn is a major challenge in industries such as telecom and subscription-based services. Retaining existing customers is more cost-effective than acquiring new ones.

Businesses need to:

Identify customers at high risk of churn

Understand the main drivers behind churn

Take proactive actions to improve retention

This project addresses these challenges using predictive modeling and data analysis.

🛠️ Tools & Technologies

Python

Pandas

NumPy

Scikit-learn

XGBoost

Matplotlib – Model evaluation visualizations

Jupyter Notebook – Data analysis & modeling

📁 Dataset

Telco Customer Churn Dataset (Kaggle)

Includes:

Customer demographics

Subscription and service usage details

Contract and payment information

Churn label (Yes / No)

⚙️ Project Workflow

Data cleaning and preprocessing

Feature engineering (tenure, charges, services, contracts)

Encoding categorical variables

Training classification models

Evaluating model performance

Analyzing feature importance

Interpreting results for business insights

🧠 Modeling Approach

Binary classification problem (Churn vs No Churn)

Train-test split for evaluation

Performance evaluated using:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

Feature importance analysis to identify churn drivers

📊 Model Evaluation & Results
✅ Overall Performance

Accuracy: 78.5%

📈 Classification Metrics

Precision (Churn = 1): 63%

Recall (Churn = 1): 48%

F1-score (Churn = 1): 54%

The model performs well overall, with reasonable churn prediction capability. Recall can be further improved through threshold tuning or class imbalance handling.

🔍 Confusion Matrix Summary

True Negatives: 927

False Positives: 106

False Negatives: 196

True Positives: 178

The model accurately predicts most non-churn customers and identifies a significant portion of churn cases.

📌 Feature Importance – Key Churn Drivers

The most influential features affecting churn were:

TotalCharges

MonthlyCharges

Tenure

Internet Service (Fiber Optic)

Payment Method (Electronic Check)

Contract Type

Online Security & Tech Support

These factors provide strong insights into customer behavior and churn risk.

💡 Key Business Insights

Customers with high monthly charges and low tenure are at higher risk of churn

Month-to-month contracts show higher churn rates

Electronic check payment method is strongly associated with churn

Availability of online security and tech support reduces churn probability

🚀 Outcome

This project demonstrates practical skills in:

Classification and predictive modeling

Customer churn analysis

Model evaluation and interpretation

Translating ML results into business insights

The project aligns well with entry-level machine learning and data analytics roles.# FUTURE_ML_02
Churn prediction system built using machine learning on telecom customer data.
