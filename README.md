# 🩺 Heart Disease Prediction Project

This project focuses on predicting the presence of heart disease using patient health data. It was completed as part of the **CS 301: Introduction to Data Science** course at NJIT.

## 🔍 Overview

Using a real-world healthcare dataset, we performed:

- 📊 **Exploratory Data Analysis (EDA)**: Visualized key patterns and distributions
- 🧹 **Data Preprocessing**: Handled missing values, encoded categorical features, and cleaned the dataset
- 🤖 **Modeling**: Trained four classification models — Logistic Regression, K-Nearest Neighbors (KNN), Naive Bayes, and Support Vector Machine (SVM)
- 📈 **Evaluation**: Assessed models using Accuracy, Precision, Recall, and F1 Score
- ⚖️ **Comparison**: Compared all models and selected the top two (Naive Bayes & SVM) based on performance in a healthcare context

## 🧠 Key Takeaway

In healthcare, **recall is critical** - missing a diagnosis can be more harmful than a false positive. Based on our results:
- **SVM** had the highest recall (0.90)
- **Naive Bayes** offered a balanced performance with fewer false positives

Both models were strong contenders, and we discussed the trade-offs between them in the final comparison.

## 📁 Files

- `heart.csv`: Original dataset downloaded from Kaggle
- `heart_clean.csv`: Cleaned dataset used for modeling
- `Vis.ipynb`: Notebook for EDA and data preprocessing
- `Model_Comparison.ipynb`: Full modeling and evaluation pipeline

## 👥 Contributors

- Andrew Anil George
- Christian Sodora
- Sami Kuloglu

## 🧪 Tools Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- scikit-learn