# Breast Cancer Survival Prediction using Machine Learning

## Overview

This project predicts breast cancer patient outcomes using machine learning models.
The goal is to help in early prognosis by analyzing clinical features and predicting survival status.

The project compares multiple machine learning algorithms and evaluates their performance using accuracy, F1-score, and ROC-AUC.



## Problem Statement

Breast cancer is one of the leading causes of death among women worldwide.
Early prediction of survival outcomes can help in better treatment planning.

Manual prognosis can be slow and error-prone, so machine learning models can provide a data-driven solution.



## Models Used

- K-Nearest Neighbors
- Logistic Regression
- Decision Tree
- Random Forest (Tuned)
- XGBoost Classifier

SMOTE was used to handle class imbalance.

GridSearchCV was used for hyperparameter tuning.



## Results

Best model: Random Forest (Tuned)

Accuracy ≈ 90.6%

Performance comparison:

See results folder for model comparison and decision tree visualization.



## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Imbalanced-learn (SMOTE)
- Matplotlib
- Seaborn
- Jupyter Notebook



## Files in Repository

- Final_Breast_Cancer_Project.ipynb → main notebook
- ML_Final_Project_Report.pdf → project report
- requirements.txt → libraries
- results/ → model outputs
- data/ → dataset which is not included


## Dataset

Dataset not included in repository.

If needed, place dataset inside `data/` folder.



## Future Improvements

- Try deep learning models
- Deploy as web app
- Use larger clinical dataset



## Author

Niyathi Lekkala  
Master's in Computer Science
