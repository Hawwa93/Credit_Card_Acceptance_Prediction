**Loan Prediction Machine Learning Project**

This project demonstrates a complete end-to-end machine learning pipeline for binary classification. The goal is to predict whether a loan applicant is likely to be approved based on various demographic,
financial, and personal attributes. Through exploratory data analysis, model comparison, and evaluation, the project identifies the most impactful predictors and selects the most accurate model to support informed decision-making in real-world financial scenarios.

**Problem Statement**

Financial institutions receive thousands of loan applications every day. Automating the process of predicting whether a loan should be approved or not can help banks:
- Minimize financial risk.
- Speed up the loan approval process.
- Provide better customer service.

**Dataset**

The dataset used is a modified version of the popular Loan Prediction dataset available on Kaggle. It consist of 5000 rows and 14 features includint the target **(CreditCard)**.
The dataset contains information such as:
- Gender, Marital Status, Education
- Income and Loan Amount
- Credit History, Property Area
- Loan Status (Target)
- 
**Exploratory Data Analysis (EDA)**
- Handled missing values and outliers.
- Performed univariate and bivariate analysis.
- Visualized distributions and relationships using `matplotlib` and `seaborn`.

**Data Preprocessing**
- Encoding of categorical variables using Label Encoding.
- Scaling of numerical features using StandardScaler.
- Handled class imbalance using **upsampling** on the minority class.

**Machine Learning Models Used**
Itrained and evaluated several classification models:
- **Decision Tree**
- **Random Forest**
- **XGBoost**
- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM)**
- **Logistic Regression**

**Each model was assessed using:**
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score

**Conclussion**
The best-performing model (RandomForestClassifier) is saved using joblib and ready for deployment in a production environment or web app.
