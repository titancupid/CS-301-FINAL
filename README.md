# Heart Failure Prediction using ML

This project focuses on predicting the presence of heart disease using patient health data. It was completed as part of the **CS 301: Introduction to Data Science** course at NJIT.

## Overview

Using a real-world healthcare dataset, we performed:

- **Exploratory Data Analysis (EDA)**: Visualized key patterns and distributions
- **Data Preprocessing**: Handled missing values, encoded categorical features, and cleaned the dataset
- **Modeling**: Trained four classification models - Logistic Regression, K-Nearest Neighbors (KNN), Naive Bayes, and Support Vector Machine (SVM)
- **Evaluation**: Assessed models using Accuracy, Precision, Recall, and F1 Score
- **Comparison**: Compared all models and selected the top two (Naive Bayes & SVM) based on performance in a healthcare context

## Key Takeaway

In the context of healthcare, **recall is especially important** because it’s often more harmful to miss a diagnosis than to raise a false alarm. Based on our results, the **Support Vector Machine (SVM)** model achieved the highest recall, making it highly effective at identifying patients with heart disease. Meanwhile, the **Naive Bayes** model provided a more balanced performance, with fewer false positives. 

Both models proved to be strong candidates, and we carefully weighed their trade-offs during our final comparison.

## Files

- `heart.csv`: Original dataset downloaded from Kaggle
- `heart_clean.csv`: Cleaned dataset
- `Heart_Clean.ipynb`: Data Preprocessing
- `Vis.ipynb`: Data Visualization
- `Model_Comparison.ipynb`: Modeling, Evaluation, and Comparison

## Contributors

- Andrew Anil George
- Christian Sodora
- Sami Kuloglu

## Tools Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- scikit-learn
