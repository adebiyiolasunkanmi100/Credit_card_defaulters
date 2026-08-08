## Machine Learning Approach to Identifying Repayment Risk and Strengthening Credit Assessment Decisions

## 📌 Project Review
Financial institutions lose billions annually due to loan defaults.  
Accurately identifying customers likely to default before granting or extending credit enables banks to reduce financial risk and make better lending decisions.

This project develops and evaluates multiple machine learning classification models to predict whether a customer will default on their next credit card payment using demographic information, credit history, billing records, and repayment behaviour.

---

## 🔄 Workflow
The project follows a complete end‑to‑end Data Science pipeline:

1. Data Cleaning  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering  
4. Data Preprocessing  
5. Train‑Test Split  
6. Model Development  
7. Class Imbalance Handling (Class Weights & SMOTE)  
8. Hyperparameter Tuning  
9. Threshold Optimization  
10. Model Evaluation  
11. Feature Importance Analysis  
12. Business Recommendations  

---

## 📂 Dataset
- **Source:** [UCI Default of Credit Card Clients Dataset](https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients)  
- **Contents:**  
  - Customer demographics  
  - Credit limits  
  - Historical repayment records  
  - Bill statements  
  - Payment amounts  
  - Target variable: default on next month’s payment  

---

## 💡 Business Problem
Banks face significant financial losses when customers fail to repay loans.  
The objective is to build a predictive model capable of identifying high‑risk customers, enabling institutions to:

- Improve credit approval decisions  
- Reduce lending risk  
- Identify high‑risk customers early  
- Strengthen portfolio management  

---

## 🎯 Objectives
- Perform EDA to identify factors associated with loan default  
- Build and compare multiple classification models  
- Handle class imbalance effectively  
- Optimize model performance with hyperparameter tuning & threshold adjustment  
- Interpret important predictors  
- Provide actionable business recommendations  

---

## 🛠️ Technologies Used
- **Languages & Libraries:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit‑Learn, XGBoost  
- **Environment:** Jupyter Notebook  

### Models Evaluated
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Gradient Boosting  
- Extra Trees  
- XGBoost  

### Class Imbalance Strategies
- Class Weighting  
- SMOTE (Synthetic Minority Oversampling Technique)  

### Optimization
- RandomizedSearchCV for hyperparameter tuning  
- Threshold optimization for balancing precision & recall  

---

## 📊 Model Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1‑Score  
- ROC‑AUC  
- Confusion Matrix  
- ROC Curve  

> Because the dataset is imbalanced, **F1‑score** and **ROC‑AUC** were prioritized when selecting the final model.

---

## 🔑 Key Findings
- Previous repayment behaviour strongly influences future loan default.  
- Customers with repeated payment delays are significantly more likely to default.  
- Credit limit and historical payment information contribute substantially to prediction performance.  
- Handling class imbalance improved identification of high‑risk customers.  
- Threshold optimization enhanced the balance between precision and recall.  

---

## 📌 Business Recommendations
- Monitor customers with poor repayment history more closely.  
- Develop an early warning system for high‑risk borrowers.  
- Incorporate repayment behaviour into lending decisions.  
- Review credit limits for customers with elevated default risk.  
- Periodically retrain the predictive model with updated customer data.  

---

## 📁 Repository Structure

### Author
Adebiyi Olasunkanmi
M.Sc. Business administration | Machine Learning engineer | Data Science Enthusiast

GitHub: https://github.com/adebiyiolasunkanmi100
