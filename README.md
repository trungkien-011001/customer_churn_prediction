# Customer Churn Prediction
In this personal project, I have applied machine learning models into predicting numbers of churned customers. The project helps business to minimize the risk from churned customers that causes revenue loss by predicting whether they are a churned customer based on their feature.

---
## ✅ Project Overview
In this personal project, I have handle a small dataset called 'Telco-Customer-Churn'. The project used various models such as Logistic Regression, Decision Tree, Random Forest, XGBoost to train and test the dataset. Logistic Regression performed the best among 4 model due to the preference of the data features and data size. However, I believed with a bigger and non-linear feature dataset, LR is not as good as the others.

---
## 🧱 Process:
1. Data Collection: Download .csv file from https://www.geeksforgeeks.org/machine-learning/python-customer-churn-analysis-prediction/
2. Data Cleaning: Handle mismatched datatype columns, relacing null values with the median value for numeric type columns, dropping unnessary columns such as ID
3. Feature Engineering: Using One-Hot Encoder and StandardScaler for standardizing categorical and numeric type columns for model training
4. Model Training: LR, Decision Tree, Random Forest and XGBoost
5. Model Evaluation: Using Accurary, Precision, Recall, Confusion Matrix, F1, ROC-AUC
6. Model Tuning: Choosing the best-performed model to tune the Recall Score for minimizing the numbers of False Negative cases

---
## 🛠️ Tools
- Programming Language: Python 3.8+
- Libraries: pandas, numpy, matplotlin, seaborn, sklearn, xgboost
- IDE: VSCode Studio (Jupiter Notebook file)

---
📄 License
Using for learning and researching purposes
