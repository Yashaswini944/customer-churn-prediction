📌 Customer Churn Prediction — End‑to‑End Machine Learning Project

🚀 Overview
This project builds a complete, production‑style machine learning pipeline to predict customer churn for a telecom company. It covers everything from data cleaning and feature engineering to model optimization and business insights.
The final Gradient Boosting model delivers strong recall and ROC‑AUC, making it effective for identifying customers at high risk of leaving.

🧠 Problem Statement
Customer churn is one of the biggest challenges for subscription‑based businesses.
The goal of this project is to:

Predict which customers are likely to churn

Understand the key drivers behind churn

Provide actionable recommendations to reduce churn

🧠 Problem Statement
Customer churn is one of the biggest challenges for subscription‑based businesses.
The goal of this project is to:

Predict which customers are likely to churn

Understand the key drivers behind churn

Provide actionable recommendations to reduce churn

🛠️ Machine Learning Pipeline
The project follows a full, industry‑standard ML workflow:

1. Data Preprocessing
Handle missing values

Convert TotalCharges to numeric

Encode categorical variables

Scale numerical features

2. Handling Class Imbalance
Applied SMOTE to balance churn vs. non‑churn customers

3. Model Training
Trained multiple models:

Logistic Regression

Random Forest

Gradient Boosting

4. Hyperparameter Tuning
RandomizedSearchCV

GridSearchCV

Optimized Gradient Boosting selected as final model

5. Evaluation Metrics
Accuracy

Precision

Recall

F1‑Score

ROC‑AUC

Confusion Matrix

🏆 Final Model
Gradient Boosting Classifier

Why this model?  
It achieved the best balance of:

High recall for churners

Strong ROC‑AUC

Stable performance across folds

This makes it ideal for real‑world retention strategies.

🔍 Feature Importance
Top drivers of churn identified by the model:

Month‑to‑month contracts

Low tenure

High monthly charges

Electronic check payments

Lack of tech support

These insights directly inform business strategy.

💡 Business Recommendations
Based on the model’s insights:

Offer incentives for long‑term contracts

Improve onboarding for new customers

Provide loyalty pricing for fiber customers

Encourage autopay or credit card payments

Bundle tech support with mid‑tier plans

These actions can significantly reduce churn and improve customer retention.

📁 Project Structure
├── Churn_Prediction_Project.ipynb
├── churn_model.pkl
├── requirements.txt
└── README.md


