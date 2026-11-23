Loan Risk Assessment System using Logistic Regression
Problem Statement
Banks need a reliable way to assess loan applications and determine which applicants are likely to repay their loans. This project uses machine learning to predict loan approval status based on applicant demographics, financial information, and credit history, helping financial institutions make faster and more informed lending decisions.

## Dataset
Name: Loan Prediction Dataset
Source: Kaggle / Public GitHub Dataset
Link: https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problemdataset
Rows / Columns: 614 rows, 13 columns (before preprocessing)
Tools Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
StandardScaler
Logistic Regression
Workflow
Data Collection
Data Cleaning & Missing Value Imputation
Exploratory Data Analysis (EDA)
Feature Engineering
Data Encoding & Scaling
Model Building (Logistic Regression)
Model Evaluation
Insights & Recommendations
Results
Model: Logistic Regression

Key Metrics:

Accuracy = 86.18%
Precision = 84.00%
Recall = 98.82%
F1-Score = 90.81%
Top Factors / Drivers:

Credit History – The strongest predictor of loan approval; applicants with a positive credit history were significantly more likely to receive approval.
Total Income – Higher combined applicant and co-applicant income improved approval chances.
Loan-to-Income Ratio – Applicants requesting loans that represented a smaller proportion of their total income were more likely to be approved.
## Key Findings
Credit History showed the strongest relationship with loan approval outcomes.
Applicants with strong repayment histories had substantially higher approval rates.
Engineered features such as total_income and loan_income_ratio improved the model's ability to distinguish between approved and rejected applications.
The model achieved very high recall for approved loans, correctly identifying most eligible borrowers.
The confusion matrix revealed that the model was better at identifying approvals than rejections, suggesting potential class imbalance.
## Screenshots

Images/credit_history_vs_approval.png
Images/confusion_matrix.png
## Recommendations
Implement class balancing techniques such as SMOTE or class-weight adjustments to improve rejection prediction.
Compare Logistic Regression with Decision Trees, Random Forests, and XGBoost models for potentially better performance.
Perform hyperparameter tuning to further optimize model accuracy and precision.
Explore additional applicant financial metrics to strengthen risk assessment capabilities.
Future Improvements
Train and compare Decision Tree and Random Forest classifiers.
Use ROC-AUC analysis for model comparison.
Build a loan approval prediction dashboard using Power BI or Streamlit.
Deploy the model as a web application for real-time loan eligibility assessment.

## Author
[Edwin Nkengafac] [https://www.linkedin.com/in/edwin-nkengafac-27137a2b3/]
