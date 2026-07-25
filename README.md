<<<<<<< HEAD
Heart Disease Prediction Analysis
An end-to-end data analysis and machine learning project that explores patient health data to identify risk factors for heart disease and build predictive models using Python, pandas, and scikit-learn.
📌 Project Overview
This project explores a heart disease dataset to understand which clinical and lifestyle factors are most associated with heart disease, and builds a model that can predict risk based on patient attributes.
🎯 Objectives
Explore and clean the dataset to understand its structure and quality
Identify key risk factors through exploratory data analysis (EDA)
Build and evaluate machine learning models to predict heart disease presence
Summarize insights in a way that's useful for both technical and non-technical audiences
🗂️ Dataset
Source: Kaggle
Description: Patient-level clinical data including features such as age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, ECG results, max heart rate, exercise-induced angina, and target diagnosis (presence/absence of heart disease)
🛠️ Tools & Technologies
Language: Python
Libraries: pandas, NumPy, matplotlib, seaborn, scikit-learn (KNeighborsClassifier, LogisticRegression, RandomForestClassifier, GridSearchCV, RandomizedSearchCV)
Environment: Jupyter Notebook (VS Code)
🔍 Project Workflow
Data Cleaning — Handled missing values, checked data types, removed inconsistencies
Exploratory Data Analysis (EDA) — Visualized distributions, correlations, and relationships between features and heart disease outcomes
Feature Engineering — Prepared and transformed features for modeling
Model Building — Trained and compared three classification models: K-Nearest Neighbors, Logistic Regression, and Random Forest
Hyperparameter Tuning — Optimized models using RandomizedSearchCV and GridSearchCV
Model Evaluation — Assessed performance using accuracy, precision, recall, F1-score, confusion matrix, and ROC curve
Feature Importance — Analyzed model coefficients to identify the strongest predictors of heart disease
Insights & Recommendations — Summarized key findings and their practical implications
📊 Key Findings
Logistic Regression was the best-performing model, achieving ~90% baseline accuracy and 88.5% after hyperparameter tuning (C = 0.191, solver = liblinear) — outperforming Random Forest (88.5% → 86.9% after tuning) and KNN (67.2% → 75.4% after tuning)
The final model achieved 89% precision and 91% recall for detecting heart disease cases, with an overall accuracy of 89% on the test set
Chest pain type (cp) and ST segment slope were the strongest positive predictors of heart disease presence
Sex, thalassemia (thal), and number of major vessels (ca) were the strongest negative predictors in this dataset
Chest pain type showed the highest correlation (0.43) with heart disease diagnosis among all features
📈 Visual Highlights
Load image
Age Distribution
�
Load image
Comparison of Sex to Possibility of Heart Disease
�
Load image
Correlation Between Age and Max Heart Rate (thalach)
�
Load image
Correlation Heatmap
�
Load image
Relationship Between Chest Pain and Heart Disease
�
Load image
KNN Train vs Test Score
�
Load image
Feature Importance (Logistic Regression Coefficients)
�
Load image
ROC Curve
�
📁 Repository Structure
Code
🚀 How to Run
Clone this repository:
Bash
Open the folder in VS Code or Jupyter
Install required libraries:
Bash
Open notebook/Heart Disease.ipynb and run cell by cell
👤 Author
Emem Ejikeme
Data Analyst | Aspiring ML Practitioner
GitHub Profile
This project is part of an ongoing portfolio demonstrating skills in data cleaning, exploratory analysis, and predictive modeling using Python.
=======
# heart_disease
>>>>>>> 5e1ed68779b6cbb7bfca2fa037256533314a8348
