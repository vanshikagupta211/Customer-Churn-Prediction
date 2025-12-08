📊 Customer Churn Prediction – Machine Learning Project

By Vanshika Gupta

🔍 Project Overview

This project builds an end-to-end customer churn prediction model for a telecom company.
The goal is to identify customers who are likely to churn so the business can take proactive retention actions.

The project includes:

Data cleaning & preprocessing

Exploratory Data Analysis (EDA)

Handling class imbalance using SMOTE

Feature encoding & scaling

Model training using 6 ML algorithms

Model comparison using Accuracy, Recall, F1, ROC-AUC

Business insights & final recommendations

🔧 Technologies Used

Python

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn

Imbalanced-learn (SMOTE)

XGBoost

🔧 Project Workflow

Data Cleaning

Removed blanks

Converted TotalCharges to numeric

Filled missing values

EDA

Churn distribution

Feature relationships

Boxplots & histograms

Correlation heatmap

Feature Engineering

Encoding categorical variables

Separating X and y

Standard scaling

Imbalance Handling

Applied SMOTE after train-test split

Model Training
Trained the following models:

Logistic Regression

Decision Tree (with tuning)

Random Forest

Gradient Boosting

XGBoost

AdaBoost

Model Evaluation
Compared performance based on:

Accuracy

Precision

Recall

F1-score

ROC-AUC

Model Selection
Gradient Boosting selected as the final model due to best balanced performance.

Business Insights & Recommendations
Provided actionable insights to reduce churn.

📈 Final Model Selection

Based on Accuracy, Recall, F1-score, and ROC-AUC:

Gradient Boosting → Best overall performance

AdaBoost → Highest recall (0.88), best for catching churners

Logistic Regression → Highly interpretable with strong AUC

Final chosen model: Gradient Boosting

📈 Business Insights

Key drivers of churn:

Month-to-month contracts

Fiber optic internet service

Lack of security & tech support services

High monthly charges

Low tenure (new customers churn more)

Payment method: Electronic check

📌 Recommendations

Offer discounts to convert month-to-month customers

Improve fiber service quality

Bundle security/tech support services

Provide retention offers to high-charge users

Strengthen onboarding for new customers

📈 How to Run the Project
pip install -r requirements.txt

## Open the Notebook

[Customer Churn Prediction.ipynb](Customer%20Churn%20Prediction.ipynb)

🔧 Folder Structure
Customer-Churn-Prediction/
│
├── Customer_Churn_Prediction.ipynb
├── README.md
├── requirements.txt
└── customer_churn.csv   

👩‍💻 Author

Vanshika Gupta

Data Analyst | Machine Learning | Python | Power BI
