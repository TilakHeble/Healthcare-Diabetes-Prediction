# Healthcare Diabetes Prediction

## Project Overview

This project develops a machine learning solution to predict diabetes risk using healthcare and clinical data. The objective is to identify patients at higher risk of diabetes and support early intervention through data-driven decision-making.

The project follows a complete data science workflow, including data cleaning, exploratory data analysis, feature engineering, predictive modeling, model evaluation, and dashboard reporting.

---

## Business Problem

Diabetes is one of the most prevalent chronic diseases worldwide and can lead to serious health complications if not detected early.

Healthcare providers require effective methods to identify high-risk patients using available clinical information. This project aims to develop a predictive model that can support early diabetes screening and improve healthcare outcomes.

---

## Dataset

The dataset contains 768 patient records and includes clinical measurements such as:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age
- Outcome (Diabetic / Non-Diabetic)

Source: National Institute of Diabetes and Digestive and Kidney Diseases (NIDDK)

---

## Project Workflow

### 1. Data Understanding & Quality Assessment
- Dataset inspection
- Missing value identification
- Data quality assessment
- Median imputation

### 2. Exploratory Data Analysis
- Distribution analysis
- Correlation analysis
- Outcome analysis
- Risk factor investigation

### 3. Feature Engineering
- Age groups
- BMI categories
- Glucose risk categories
- Pregnancy categories

### 4. Model Development
The following machine learning models were evaluated:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Gradient Boosting

### 5. Model Evaluation
Evaluation metrics included:

- Accuracy
- Precision
- Recall (Sensitivity)
- F1 Score
- ROC-AUC
- Specificity

---

## Results

The Random Forest model was selected as the final model due to its strong balance between predictive performance and sensitivity.

### Final Model Performance

| Metric | Value |
|----------|----------|
| Accuracy | 75.3% |
| Precision | 64.8% |
| Recall | 64.8% |
| F1 Score | 64.8% |
| ROC-AUC | 81.7% |

---

## Key Findings

- Glucose was the strongest predictor of diabetes.
- Higher BMI values were associated with increased diabetes risk.
- Older age groups exhibited higher diabetes prevalence.
- Feature engineering improved model interpretability and risk segmentation.
- Random Forest provided the best balance between accuracy and recall.

---

## Dashboard

A Tableau dashboard was developed to support healthcare decision-making and population risk analysis.

Dashboard components include:

- Diabetes population overview
- Clinical risk factor analysis
- Distribution analysis
- Correlation heatmap
- Age group risk analysis

---

## Technologies Used

### Programming
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- SciPy

### Visualization
- Tableau

---

## Repository Structure

```text
Healthcare-Diabetes-Prediction/
│
├── data/
├── notebooks/
├── dashboard/
├── README.md
├── requirements.txt
└── .gitignore
