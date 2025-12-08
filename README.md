# 📊 Customer Churn Prediction – Machine Learning Project
### **By Vanshika Gupta**

---

## 🔍 Project Overview

This project builds an **end-to-end customer churn prediction model** for a telecom company.
The goal is to **identify customers who are likely to churn** so the business can take proactive retention actions.

### The project includes:

- Data cleaning & preprocessing  
- Exploratory Data Analysis (EDA)  
- Handling class imbalance using **SMOTE**
- Feature encoding & scaling  
- Model training using 6 ML algorithms 
- Model comparison (Accuracy, Recall, F1, ROC-AUC)  
- Business insights & final recommendations 

---

## 🔧 Technologies Used

Python,
Pandas, NumPy,
Matplotlib, Seaborn,
Scikit-learn,
Imbalanced-learn (SMOTE),
XGBoost

---

## 🔧 Project Workflow

### **1. Data Cleaning**
- Removed blank spaces  
- Converted *TotalCharges* to numeric  
- Filled missing values  

### **2. Exploratory Data Analysis (EDA)**
- Churn distribution  
- Categorical & numerical distributions  
- Boxplots & histograms  
- Correlation heatmap  

### **3. Feature Engineering**
- One-hot encoding  
- Separating X and y  
- Standard scaling  

### **4. Imbalance Handling**
- Applied **SMOTE** *after* train-test split  

### **5. Model Training**
Trained the following models:

- Logistic Regression  
- Decision Tree (tuned using RandomizedSearchCV)  
- Random Forest  
- Gradient Boosting  
- XGBoost  
- AdaBoost  

### **6. Model Evaluation**
Compared performance based on:

- Accuracy  
- Precision  
- Recall  
- F1-score  
- ROC-AUC  

### **7. Model Selection**
➡️ **Gradient Boosting** selected as the final model (best balanced performance).

---

## 📈 Final Model Selection

**Based on Accuracy, Recall, F1-score, and ROC-AUC:**

| Model | Key Strength |
|-------|--------------|
| **Gradient Boosting** |  Best overall balanced performance |
| **AdaBoost** |  Highest recall (0.88) — best for catching churners |
| **Logistic Regression** |  Most interpretable with strong AUC |

✔ **Final chosen model: Gradient Boosting**

---

## 📈 Business Insights

Top churn indicators:

- **Month-to-Month contracts** → highest churn  
- **Fiber Optic** internet users churn more  
- Missing **security/tech support services** increases churn  
- **High monthly charges** push customers away  
- **Low tenure** customers churn quickly  
- **Electronic Check** payment users have the highest churn rate  

---

## 📌 Recommendations

- Offer discounts to convert month-to-month users  
- Improve fiber internet service quality  
- Bundle security + tech support services  
- Provide retention offers to high-billing users  
- Strengthen onboarding for new customers  

---

## 📈 How to Run the Project

Install dependencies:

```
pip install -r requirements.txt
```

## Open the Notebook

[Customer Churn Prediction.ipynb](Customer%20Churn%20Prediction.ipynb)

## Folder Structure

```
Customer-Churn-Prediction/
│
├── Customer_Churn_Prediction.ipynb
├── README.md
├── requirements.txt
└── customer_churn.csv   
```

👩‍💻 Author

Vanshika Gupta

Data Scientist | Machine Learning | Python


