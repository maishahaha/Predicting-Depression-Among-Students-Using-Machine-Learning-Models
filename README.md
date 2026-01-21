# Predicting Depression Among Students Using Machine Learning

This repository contains the implementation and research paper for the project **“Predicting Depression Among Students Using Machine Learning Models”**. The study investigates how different machine learning algorithms can be used for early screening of depression among students.

## Overview
- **Problem:** Depression prediction (binary classification)
- **Dataset:** [Student Depression Dataset.](https://www.kaggle.com/datasets/hopesb/student-depression-dataset)
- **Approach:** Classical ML + ensemble models
- **Class imbalance handling:** SMOTE
- **Evaluation metrics:** Accuracy, F1-score

## Models Used
- Logistic Regression  
- Decision Tree  
- Random Forest  
- K-Nearest Neighbors (KNN)  
- AdaBoost  
- Gradient Boosting  

Hyperparameter tuning was performed using GridSearchCV.

## Results
- **Best performing model:** AdaBoost  
- **Accuracy:** 85.02%  
- **F1-score:** 87.21%  
- Ensemble-based models consistently outperformed individual classifiers.


## Technologies
- Python
- Pandas, NumPy
- Matplotlib
- Scikit-learn
- Imbalanced-learn (SMOTE)

## Notes
This project is intended for **research and academic purposes only** and should be used as a decision-support or screening tool, not as a clinical diagnostic system.

