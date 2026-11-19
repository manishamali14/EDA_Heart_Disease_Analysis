# Heart Disease Analysis

This project looks at a heart disease dataset to find which factors are linked to heart disease, using data cleaning, exploratory analysis and a logistic regression model.

## Dataset

[Kaggle Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset) with 1025 rows and 14 columns.

## Tools

Python, Pandas, NumPy, Matplotlib, Seaborn, SciPy and Scikit learn

## Data Cleaning

* Removed 723 duplicate rows, leaving 302 patients
* Filled invalid ca and thal values with the most common value
* Kept 20 outliers as they are real patient readings
* Scaled the clinical columns with StandardScaler

## Key Findings

* Major vessels, chest pain type, exercise induced angina, oldpeak, max heart rate and thalassemia are most linked to heart disease
* Cholesterol, blood pressure and blood sugar show only a weak link
* The logistic regression model reached 85.2% accuracy and a ROC AUC of 0.906
