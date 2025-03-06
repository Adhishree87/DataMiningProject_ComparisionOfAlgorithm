<h1 align="center"> Water Potability Classification Using Machine Learning Algorithms </h1>

---

## 📌 Dataset Information
- **Source:** [Kaggle Water Potability Dataset](https://www.kaggle.com/datasets/uom190346a/water-quality-and-potability)  
- **Features:** pH, Hardness, Solids, Chloramines, Sulfates, Conductivity, Organic Carbon, Trihalomethanes, Turbidity, Potability  
- **Rows:** 11,115  
- **Missing Values:** pH, Sulfates, Trihalomethanes  

---

## Data Preprocessing
- Missing values imputed with **mean** strategy  
- Outliers handled using **IQR (Interquartile Range)** method  

---

## Models Implemented  
- Random Forest   
- Decision Tree  
- Logistic Regression 
- K-Nearest Neighbors (KNN)   
- Support Vector Machine (SVM) 

---

## Results  

| Model               | Accuracy | F1 Score |
|-------------------|----------|---------|
| **Random Forest** | **98.52%** | **98.07%** |
| KNN               | 75.53%   | 67.62%  |
| Decision Tree     | 65.81%   | 29.50%  |
| SVM              | 61.22%   | 0.69%   |
| Logistic Regression | 61.22% | 0.00%   |

---

## 🔥 Best Performing Model  
✅ **Random Forest** with the highest accuracy and F1 Score.

---

## 📌 Conclusion  
Random Forest emerged as the most effective model for predicting water potability, offering robust performance across all key evaluation metrics.

---
