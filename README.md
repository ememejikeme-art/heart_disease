# Heart Disease Prediction Analysis

An end-to-end data analysis and machine learning project that explores patient health data to identify risk factors for heart disease and build predictive models using Python, pandas, and scikit-learn.

## 📌 Project Overview

This project explores a heart disease dataset to understand which clinical and lifestyle factors are most associated with heart disease, and builds a model that can predict risk based on patient attributes.

## 🎯 Objectives

- Explore and clean the dataset to understand its structure and quality
- Identify key risk factors through exploratory data analysis (EDA)
- Build and evaluate machine learning models to predict heart disease presence
- Summarize insights in a way that's useful for both technical and non-technical audiences

## 🗂️ Dataset

- **Source:** Kaggle
- **Description:** Patient-level clinical data including features such as age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, ECG results, max heart rate, exercise-induced angina, and target diagnosis (presence/absence of heart disease)

## 🛠️ Tools & Technologies

- **Language:** Python
- **Libraries:** pandas, NumPy, matplotlib, seaborn, scikit-learn
- **Environment:** Jupyter Notebook (VS Code)

## 🔍 Project Workflow

1. **Data Cleaning** — Handled missing values, checked data types, removed inconsistencies
2. **Exploratory Data Analysis (EDA)** — Visualized distributions, correlations, and relationships between features and heart disease outcomes
3. **Feature Engineering** — Prepared and transformed features for modeling
4. **Model Building** — Trained and compared classification models: K-Nearest Neighbors, Logistic Regression, and Random Forest
5. **Hyperparameter Tuning** — Optimized models using RandomizedSearchCV and GridSearchCV
6. **Model Evaluation** — Assessed performance using accuracy, precision, recall, F1-score, confusion matrix, and ROC curve
7. **Insights & Recommendations** — Summarized key findings and their practical implications

## 📊 Key Findings

- **Logistic Regression was the best-performing model**, achieving ~90% baseline accuracy and 88.5% after hyperparameter tuning — outperforming Random Forest and KNN
- The final model achieved **89% precision and 91% recall** for detecting heart disease cases, with an overall accuracy of 89% on the test set
- **Chest pain type** and **age** showed clear relationships with heart disease presence
- **Sex** also showed a notable relationship with likelihood of heart disease in this dataset

## 📈 Visual Highlights

**Age Distribution**
![Age Distribution](Images/Age%20distribution.png)

**Comparision of Sex to Possibilities of heart_disease**
![Comparison of Sex to heart_disease](Images/comparision%20of%20sex%20to%20possibilities%20of%20heart_disease.png)

**Correlation Heatmap**
![Correlation Heatmap](Images/Correlation%20heatmaps.png)

**Heart Disease in Function of Age**
![Heart Disease in Function of Age](Images/Heart%20Disease%20in%20function%20of%20age.png)

**Heart Disease per Chest Pain Type**
![Heart Disease per Chest Pain Type](Images/Heart%20Disease%20per%20Chest%20Pain.png)

**ROC Curve**
![ROC Curve](Images/Roc_Curve%20Score.png)

**Train vs Test Score**
![Train Test Score](Images/Train%20Test%20Score.png)

## 📁 Repository Structure

```
heart_disease/
│
├── Data/          # Raw dataset
├── Notebook/      # Main analysis notebook
├── Images/        # Exported charts used in this README
├── .gitignore     # Files/folders excluded from version control
└── README.md      # Project documentation
```

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/ememejikeme-art/heart_disease.git
   ```
2. Open the folder in VS Code or Jupyter
3. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
4. Open the notebook inside `Notebook/` and run cell by cell

## 👤 Author

**Emem Ejikeme**
Data Analyst | ML Practitioner
[GitHub Profile](https://github.com/ememejikeme-art)