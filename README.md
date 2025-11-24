# -Heart-Disease-Prediction-

-----------Task Objective-----------
The goal of this project is to build a machine learning model that predicts whether a person is at risk of heart disease using medical attributes such as age, cholesterol level, blood pressure, and chest pain type.
The task includes:

Data cleaning and preprocessing

Exploratory Data Analysis (EDA)

Training a classification model

Evaluating model performance (Accuracy, Confusion Matrix, ROC–AUC)

Identifying important features affecting heart disease prediction

-----------Dataset Used-----------

Heart Disease UCI Dataset (Kaggle)
This dataset contains multiple clinical features commonly used in cardiovascular risk analysis, including:

Age

Sex

Chest Pain Type

Resting Blood Pressure

Cholesterol

Fasting Blood Sugar

Resting ECG

Max Heart Rate Achieved

Exercise-induced Angina

ST Depression

Slope, Major Vessels, Thalassemia

Target (0 = No Heart Disease, 1 = Heart Disease)

----------- Models Applied-----------

The notebook implements the following machine learning model(s):

- Logistic Regression
- Logistic RegressionCV
- Logistic Regression + GridSeatchCV

A simple, interpretable model used for binary classification.
Evaluates how medical features contribute to the likelihood of heart disease.


-----------Key Results & Findings-----------
Model Evaluation:

Accuracy Score: Indicates how many predictions were correct

Confusion Matrix: Shows true positives, true negatives, false positives, and false negatives

ROC Curve & AUC:

ROC curve visualizes model performance across thresholds

AUC score reflects overall classification quality (higher = better)

Feature Importance

The model highlights the most influential medical predictors, such as:

Chest pain type

Maximum heart rate (thalach)

ST depression (oldpeak)

Age

Cholesterol

These insights help identify risk factors strongly associated with heart disease.

-----------Overall Summary-----------

The model provides a reliable baseline for heart disease prediction

Logistic Regression offers clear interpretability

Evaluation metrics confirm the model performs well

Feature importance analysis provides meaningful medical insights
