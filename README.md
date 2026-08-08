# Customer_loan_Prediction_Model
### Machine Learning Approach to identifying Repayment Risk and Strengthening Credict assessment Decision
## Project review
Financial institutions lose billions annually due to loan defaults. Accurately identifying customers who are likely to default before granting or extending credit enables banks to reduce financial risk and make better lending decisions.

This project develops and evaluates multiple machine learning classification models to predict whether a customer will default on their next credit card payment using demographic information, credit history, billing records, and repayment behaviour.

The project follows a complete end-to-end Data Science workflow including:

Data Cleaning
Exploratory Data Analysis (EDA)
Feature Engineering
Data Preprocessing
Machine Learning Model Development
Class Imbalance Handling
Hyperparameter Tuning
Threshold Optimization
Model Evaluation
Feature Importance Analysis
Business Recommendations
Dataset
Source: https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients

The dataset contains customer demographic information, credit limits, historical repayment records, bill statements, payment amounts, and the target variable indicating whether a customer defaulted on the next month's payment.

Business Problem
Banks face significant financial losses when customers fail to repay their loans.

The objective of this project is to build a predictive model capable of identifying customers who are at high risk of default, allowing financial institutions to:

Improve credit approval decisions
Reduce lending risk
Identify high-risk customers early
Improve portfolio management
Objectives
The project aims to:

Perform Exploratory Data Analysis (EDA)
Identify factors associated with loan default
Build multiple classification models
Compare model performance
Handle class imbalance
Optimize model performance
Interpret important predictors
Provide business recommendations
Project Workflow
Data Collection
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Data Preprocessing
        │
        ▼
Train-Test Split
        │
        ▼
Model Development
        │
        ▼
Class Imbalance Handling
(Class Weights & SMOTE)
        │
        ▼
Hyperparameter Tuning
        │
        ▼
Threshold Optimization
        │
        ▼
Model Evaluation
        │
        ▼
Feature Importance
        │
        ▼
Business Recommendations
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
XGBoost
Jupyter Notebook
Machine Learning Models
The following classification algorithms were evaluated:

Logistic Regression
Decision Tree
Random Forest
Gradient Boosting
Extra Trees
XGBoost
Different strategies for handling class imbalance were also investigated, including:

Class Weighting
SMOTE (Synthetic Minority Oversampling Technique)
Hyperparameter tuning was performed using RandomizedSearchCV, followed by decision threshold optimization to improve the balance between precision and recall.

Model Evaluation Metrics
The models were evaluated using:

Accuracy
Precision
Recall
F1-Score
ROC-AUC
Confusion Matrix
ROC Curve
Because the dataset is imbalanced, F1-score and ROC-AUC were considered the primary metrics when selecting the final model.

Key Findings
Some of the major insights include:

Previous repayment behaviour strongly influences future loan default.
Customers with repeated payment delays are significantly more likely to default.
Credit limit and historical payment information contribute substantially to prediction performance.
Handling class imbalance improved the model's ability to identify high-risk customers.
Threshold optimization further improved the balance between precision and recall.
Business Recommendations
Based on the findings:

Monitor customers with poor repayment history more closely.
Develop an early warning system for high-risk borrowers.
Incorporate repayment behaviour into lending decisions.
Review credit limits for customers with elevated default risk.
Periodically retrain the predictive model using updated customer data.
Repository Structure

├── Capstone.ipynb          # Complete Jupyter Notebook

├── README.md               # Project Documentation

└── dataset/                # Dataset 
Future Improvements

Potential enhancements include:

Deploying the model using Flask or FastAPI
Building an interactive Streamlit dashboard
Testing additional ensemble algorithms such as LightGBM and CatBoost
Performing feature selection
Applying SHAP for model explainability
Deploying the model as a credit risk prediction API
Results
The final optimized model demonstrated strong predictive performance and showed that machine learning can effectively support credit risk assessment by identifying customers at risk of default before financial losses occur.

Author
Adebiyi, A. Olasunkanmi

M.Sc. Business administration | Machine Learning engineer | Data Science Enthusiast

GitHub: https://github.com/adebiyi.olasunkanmi100
