# Heart Disease Prediction Using Machine Learning
Overview
This project aims to predict the likelihood of a person experiencing a heart attack based on medical and personal attributes using various machine learning models. The dataset used contains features such as cholesterol levels, resting blood pressure, and maximum heart rate, among others. By preprocessing the data and applying classification algorithms, this project identifies patterns and provides accurate predictions to aid medical diagnostics.

Dataset
The dataset includes medical and demographic features commonly used to assess cardiovascular health. Below are the key features:

Features:
Age: Age of the patient.
Sex: Gender of the patient (1 = male, 0 = female).
cp: Chest pain type (categorical).
trtbps: Resting blood pressure (in mm Hg).
chol: Serum cholesterol (in mg/dL).
fbs: Fasting blood sugar (> 120 mg/dL) (1 = true, 0 = false).
restecg: Resting electrocardiographic results (categorical).
thalachh: Maximum heart rate achieved.
exng: Exercise-induced angina (1 = yes, 0 = no).
oldpeak: ST depression induced by exercise relative to rest.
slp: The slope of the peak exercise ST segment.
caa: Number of major vessels (0–4) colored by fluoroscopy.
thall: Thalassemia (categorical).
Target:
Output: Presence of heart disease (1 = yes, 0 = no).
Project Objectives
Preprocess and analyze the dataset to identify and handle skewness in feature distributions.
Apply various classification models to predict heart disease.
Evaluate models using metrics like accuracy, precision, recall, F1-score, ROC-AUC, and log loss.
Compare model performance and determine the most suitable algorithm.
Key Steps
Exploratory Data Analysis (EDA):

Examined feature distributions.
Addressed skewness using transformations (log, square root, Box-Cox).
Data Preprocessing:

Handled missing values (if any).
Normalized features to ensure better performance across models.
Model Implementation:

Implemented multiple classifiers:
Logistic Regression
K-Nearest Neighbors (KNN)
Decision Tree
Random Forest
Support Vector Machines (SVM)
AdaBoost




