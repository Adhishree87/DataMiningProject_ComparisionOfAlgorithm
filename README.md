Water Potability Classification

Overview

This project compares machine learning algorithms to predict water potability using physicochemical properties from the Water Potability Dataset (Kaggle). The goal is to find the best model for classifying water as potable or non-potable.

Dataset

Source: Kaggle

Features: pH, Hardness, Solids, Chloramines, Sulfates, Conductivity, Organic Carbon, Trihalomethanes, Turbidity, Potability

Rows: 11,115

Missing Values: pH, Sulfates, Trihalomethanes

Preprocessing

Missing values imputed with mean

Outliers handled using the IQR method

Models Applied

Random Forest

Decision Tree

Logistic Regression

KNN

SVM

Results

Model

Accuracy

F1 Score

Random Forest

98.52%

98.07%

KNN

75.53%

67.62%

Decision Tree

65.81%

29.50%

SVM

61.22%

0.69%

Logistic Regression

61.22%

0.00%

Best Model

Random Forest performed best with the highest accuracy and F1 Score.

Conclusion

Random Forest is the most effective model for water potability classification due to its superior performance across key metrics.

Reference

Dataset: Kaggle Water Potability Dataset

Authors

Adhishree Acharya, Simran Mahat

License

For academic purposes only.
