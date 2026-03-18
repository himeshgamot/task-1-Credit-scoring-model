Overview

This project builds a Credit Scoring Model to predict whether an individual is creditworthy using the German Credit Dataset. The solution follows a complete machine learning pipeline including preprocessing, model training, evaluation, and visualization.

Dataset

Source: UCI Machine Learning Repository

File: german_credit_data1.csv

Target Column: kredit

1 → Good Credit

2 → Bad Credit (mapped to 0)

Tools & Technologies

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, VS Code

Workflow

Loaded and explored the dataset

Converted target variable to binary format

Encoded categorical features

Split data into training and testing sets

Applied feature scaling

Trained Logistic Regression and Random Forest models

Evaluation & Charts

Accuracy, Precision, Recall, F1-Score

Confusion Matrix (Random Forest)

ROC Curve with AUC Score

Feature Importance bar chart (Top features)

Results

Random Forest achieved better performance compared to Logistic Regression and effectively classified good and bad credit applicants.

Conclusion

The project demonstrates an end-to-end machine learning solution for financial risk assessment with proper evaluation and visualizations.

Author

Deepak Vikal
Machine Learning Intern – CodeAlpha