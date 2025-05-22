# 🩺 Diabetes Risk Prediction Using Logistic Regression in R

## Objective

To predict the presence of diabetes in patients using health and lifestyle factors through logistic regression modeling and exploratory data analysis in R.

---

## Dataset

- Source: [Kaggle – Diabetes Health Indicators Dataset](https://www.kaggle.com/datasets)
- Features: Age, BMI, HbA1c level, blood glucose level, hypertension, heart disease, smoking history, etc.
- Cleaned and prepared dataset with missing values and outliers removed.

---

## Methods Used

- Data Preprocessing: 
  - Removed missing values
  - Converted categorical variables (like gender, smoking history) into numeric/factor form
  - Removed outliers using IQR method for BMI, HbA1c, and glucose
- Modeling: 
  - Logistic Regression built using selected health metrics
  - Train-test split using `caTools`
- Model Evaluation: 
  - Confusion Matrix, Accuracy, Sensitivity, Specificity
- Statistical Analysis:
  - Chi-square test to evaluate gender–diabetes association

---

## Observations

- The logistic regression model had performance issues (accuracy near 0%) due to factor level mismatches.
- Imbalanced dataset (most cases were non-diabetic) could affect model performance.
- Confusion matrix generation error suggests need for further label encoding and validation.

---

## Key Insights

- HbA1c and glucose levels are strong indicators of diabetes.
- Gender might not be significantly associated with diabetes (as tested using chi-square).
- Proper label encoding and balancing are essential for model reliability.


## Acknowledgments
This project was completed as part of the Health Data Science curriculum at Saint Louis University.



## Acknowledgments

This project was completed as part of the Health Data Science curriculum at Saint Louis University.
