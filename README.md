# Income Classification using Machine Learning

## Overview

This project predicts whether an individual's income is **greater than 50K or less than or equal to 50K per year** using machine learning. The model is trained on demographic and employment related features such as age, education, occupation, and working hours.

This is a **binary classification problem**.

## Dataset

The dataset includes features such as:

* Age
* Workclass
* Education
* Marital Status
* Occupation
* Gender
* Capital Gain
* Capital Loss
* Hours per week
* Native Country

Target variable: **Income (<=50K or >50K)**

## Project Workflow

1. Data Loading and Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Engineering and Encoding
4. Feature Scaling using StandardScaler
5. Handling class imbalance using SMOTE
6. Train Test Split
7. Model Training and Evaluation

## Models Used

* Logistic Regression
* Decision Tree
* Random Forest
* Gradient Boosting
* XGBoost

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* ROC AUC Score

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit learn
* XGBoost

## Conclusion

The project demonstrates an end to end machine learning pipeline for predicting income levels and identifying key factors influencing higher earnings.

### Business Takeaway

* **Education and work experience strongly influence higher income levels**, indicating that skill development and qualifications play a major role in earnings.
* **Working hours and occupation type** also impact income, showing that certain professions and longer work hours are associated with higher salaries.
* The model helps **identify individuals likely to fall into higher income brackets**, which can support labor market analysis and economic research.
* Organizations and policymakers can use these insights to **understand income distribution and design better workforce or education policies**.

