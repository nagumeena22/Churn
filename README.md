FreshBasket Loyalty — Customer Churn Prediction

An end-to-end machine learning project to identify high-risk loyalty customers, segment them by churn probability and historical value, and generate actionable retention strategies.

📌 Project Overview & Objectives

Goal: Predict customer churn to prioritize retention efforts and protect revenue.

Data Horizon: January 2023 – June 2024.

Feature Cutoff Date: March 31, 2024 (prevents data leakage).

Churn Definition: Zero transactions between April 1 and June 30, 2024.

🛠️ Tech Stack

Language: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, OpenPyXL

Environment: Kaggle Notebook

Reporting: Microsoft Excel

🔄 Project Workflow

Data Loading & Cleaning: Inspect profiles, monthly activity, and labels for missing values and anomalies.

Feature Engineering: Aggregate historical transactions, spending, and engagement metrics through March 31, 2024.

Modeling & Evaluation: Train classifier; evaluate on held-out test data (ROC-AUC, F1-score, Precision, Recall, Decile Lift).

Segmentation & Recommendations: Categorize risk/value levels and assign targeted actions.

Excel Export: Save scored results to `churn_scored_customers
