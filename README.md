📌 Customer Churn Prediction — End‑to‑End Machine Learning Project

🚀 Overview
This project builds a complete, production‑style machine learning pipeline to predict customer churn for a telecom company. It covers everything from data cleaning and feature engineering to model optimization and business insights.
The final Gradient Boosting model delivers strong recall and ROC‑AUC, making it effective for identifying customers at high risk of leaving.

📂 Dataset
The dataset used is the Telco Customer Churn dataset, which contains customer demographics, account information, and service usage details.

Key columns include:

Customer tenure

Monthly and total charges

Contract type

Internet and phone services

Payment method

Churn label (Yes/No)

🔧 Data Preprocessing
Steps performed:

Removed duplicate or irrelevant columns

Handled missing values

Converted categorical variables using Label Encoding

Scaled numerical features using StandardScaler

Split data into train/test sets

🤖 Model Training
The model used for churn prediction is:

Gradient Boosting Classifier
Tuned hyperparameters

Trained on processed features

Saved as churn_model.pkl for future use

📈 Model Performance
The model was evaluated using:

Accuracy

Precision

Recall

F1‑Score

ROC‑AUC Score

Confusion Matrix

These metrics help assess how well the model identifies churn vs. non‑churn customers.

📊 Final Output: Feature Importance
The final output of the project is the Feature Importance visualization, which highlights the most influential factors contributing to customer churn.

## 📁 Project Structure

```
customer-churn-prediction/
│
├── data/
│   └── Telco-Customer-Churn.csv
│
├── notebooks/
│   └── Churn_Prediction_Project.ipynb
│
├── models/
│   └── churn_model.pkl
│
├── images/
│   ├── confusion_matrix.png
│   └── feature_importance.png
│
├── requirements.txt
└── README.md
```

🎯 Conclusion

This project demonstrates a complete end‑to‑end machine learning workflow for predicting customer churn.
The feature importance visualization provides actionable insights for business decision‑making and customer retention strategies.
