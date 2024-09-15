# Predicting-Customer-Churn-Identifying-Customers-Susceptible-to-Churn

**Overview**
This project focuses on predicting customer churn for Reder Telecom using historical customer data, such as demographics, engagement, and feedback. By leveraging machine learning techniques, the project aims to identify customers likely to churn and assist in retention strategies.

**Project Objectives**
Predict customer churn using machine learning models.
Analyze key factors that contribute to customer churn.
Provide insights to reduce churn rates and improve customer satisfaction.


**Data Description**
The dataset consists of both categorical and numerical features related to customer behaviors, engagement metrics, and service interactions:

Customer Information: Customer ID, Name, Age, Gender, Location, Segment, Email, Phone, Address.
Purchase History: Product, Frequency, Value.
Subscription Details: Plan, Start Date, End Date, Duration.
Website Usage: Page Views, Time Spent.
Clickstream Data: Action (Click, Search, Add to Cart), Page, Timestamp.
Engagement Metrics: Logins, Frequency.
Feedback: Rating, Comment.
Marketing Communication: Email Sent, Email Opened, Email Clicked.
Net Promoter Score (NPS):
Customer satisfaction score from 0 to 10.
Churn Label:
A binary indicator of whether the customer churned (1 for churn, 0 for no churn).

**Tech Stack**
Programming Language: Python
Libraries:
Pandas: Data manipulation and analysis.
NumPy: Numerical operations.
Matplotlib & Seaborn: Data visualization.
Scikit-learn: Model building and evaluation.

**Steps Taken**
Data Collection: Loaded the dataset and checked for missing values and duplicates.
Data Exploration: Visualized customer churn distribution, gender, segment, and age.
Correlation Analysis: Identified the most correlated features with churn.
Data Preprocessing:
Encoded categorical features.
Scaled numerical features.
Extracted features from nested columns (e.g., Service Interactions, Clickstream Data).
Model Development:
Built models using Logistic Regression and Decision Tree Classifier.
Model Evaluation:
Evaluated the models on training, validation, and test sets using Accuracy, Precision, Recall, and F1 Score.
Confusion Matrix: Visualized confusion matrices for both models.

**Key Insights**
The most important factors influencing churn include:
Service Interactions (Calls, Emails, Chats).
Payment History (Late Payments).
Website Usage (Page Views, Time Spent).
Net Promoter Score (NPS).

**Results**
Logistic Regression Test Accuracy: 96.91%
Decision Tree Classifier Test Accuracy: 97.31%[Predicting Customer Churn - Jupyter Notebook.pdf](https://github.com/user-attachments/files/17004174/Predicting.Customer.Churn.-.Jupyter.Notebook.pdf)
