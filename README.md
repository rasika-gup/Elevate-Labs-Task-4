# Logistic Regression - Binary Classification

## 📌 Objective
This project uses Logistic Regression to build a binary classifier using the Breast Cancer Wisconsin dataset.

## 🔧 Tools Used
- Python
- Scikit-learn
- Pandas, Matplotlib, Seaborn

## 📊 Steps Followed
1. Loaded Breast Cancer dataset from sklearn.
2. Split data into training and test sets.
3. Standardized the features.
4. Trained Logistic Regression model.
5. Evaluated model using:
   - Confusion Matrix
   - Precision & Recall
   - ROC-AUC Curve
6. Tuned the decision threshold.
7. Plotted the Sigmoid function.

## 📁 Files Included
- `logistic_regression.ipynb`: Main notebook with all steps.
- `images/`: Folder for plots or screenshots (optional).

## 📎 Dataset
Used built-in `load_breast_cancer()` from sklearn.

## ✅ Output
- Achieved high accuracy on the test set.
- Understood threshold effects on precision/recall.




Confusion Matrix:
 [[41  2]
 [ 1 70]]

Classification Report:
               precision    recall  f1-score   support

           0       0.98      0.95      0.96        43
           1       0.97      0.99      0.98        71

    accuracy                           0.97       114
   macro avg       0.97      0.97      0.97       114
weighted avg       0.97      0.97      0.97       114

![image](https://github.com/user-attachments/assets/2995b792-30d2-4fed-b867-8c21222acaa2)

Confusion Matrix with threshold=0.3:
 [[41  2]
 [ 0 71]]

Classification Report:
               precision    recall  f1-score   support

           0       1.00      0.95      0.98        43
           1       0.97      1.00      0.99        71

    accuracy                           0.98       114
   macro avg       0.99      0.98      0.98       114
weighted avg       0.98      0.98      0.98       114


![image](https://github.com/user-attachments/assets/6cdd6793-06a4-4466-8870-6a175bd91aa9)
