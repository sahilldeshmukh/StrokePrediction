# Stroke Prediction using Machine Learning

## 📘 Project Overview

This project focuses on the early prediction of strokes using various machine learning algorithms. Given the severity and global prevalence of strokes, the aim is to build a reliable model that can predict the likelihood of a stroke using patient data. The system takes into account clinical and lifestyle factors and uses well-known ML models to provide risk assessment.

## 🧠 Motivation

Stroke is one of the leading causes of death and long-term disability worldwide. Early detection can save lives and improve outcomes. Using machine learning to aid in early prediction provides a non-invasive, cost-effective, and fast alternative to traditional medical evaluations.

## 📂 Dataset

- **Source**: Kaggle Stroke Prediction Dataset
- **Size**: 5110 records
- **Features**:
  - Age, Gender, BMI
  - Average Glucose Level
  - Smoking Status
  - Hypertension
  - Heart Disease
  - Work Type, Residence Type
  - Marital Status
  - Stroke (Target variable)

## 🔧 Tools & Technologies

- **Language**: Python 3.11+
- **Libraries**:
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn`
  - `sklearn`
  - `xgboost`
- **Environment**:
  - Windows 10+
  - IDE: Jupyter Notebook / VS Code
- **Hardware Used**:
  - Intel i7 12th Gen
  - 16 GB RAM
  - 1 TB SSD

## ⚙️ Preprocessing Steps

- Missing values handled using median imputation
- One-hot encoding for categorical variables
- Random oversampling for class balancing
- Feature scaling using Standard Scaler
- Correlation matrix analysis

## 🧪 Models Implemented

| Model                | Accuracy  |
|---------------------|-----------|
| K-Nearest Neighbors | 97.42%    |
| Decision Tree       | 97.32%    |
| Random Forest       | **99.33%**|
| XGBoost             | 98.04%    |

Other models evaluated: Logistic Regression, Support Vector Machine, ANN.

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Curve

## 📊 Results

Random Forest outperformed all other models with an accuracy of 99.33% and excellent performance on other metrics as well. It was therefore selected as the final model.

## 📌 Conclusion

The use of Random Forest yielded the best results due to its robustness and ability to handle high-dimensional data. The model shows promise in assisting medical professionals with stroke risk prediction.

## 🚀 Future Work

- Integrate real-time data from wearable devices and EHRs
- Extend dataset with image and genetic data
- Deploy model into a web application
- Explore deep learning architecture
