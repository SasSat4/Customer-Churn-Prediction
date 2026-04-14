## Customer Churn Prediction

This project builds an end-to-end machine learning pipeline to predict customer churn, helping businesses identify customers likely to leave and take proactive retention measures.

## 🚀 Overview

The workflow includes data preprocessing, exploratory data analysis (EDA), feature selection, and dimensionality reduction using Linear Discriminant Analysis (LDA). Multiple models are trained and optimized to achieve reliable predictions.

## 🧠 Models Used
Logistic Regression
Random Forest
XGBoost

## ⚙️ Techniques Applied
Data Cleaning & Preprocessing
Exploratory Data Analysis (EDA)
Feature Selection (Correlation Analysis)
Dimensionality Reduction (LDA)
Stratified Cross-Validation
Hyperparameter Tuning (GridSearchCV)

## 📈 Results

All models achieved consistent performance:

Logistic Regression: 76.86% accuracy
Random Forest: 76.86% accuracy
XGBoost: 76.86% accuracy
Tuned Models (RF & XGBoost): 76.86% accuracy

The model effectively identifies customers at risk of churn, supporting data-driven decision-making.

## 📂 Dataset

You can use the dataset from here:
👉 https://www.kaggle.com/datasets/blastchar/telco-customer-churn

## 🛠️ Tech Stack
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
XGBoost

## 💡 Future Improvements
Handle class imbalance (SMOTE, class weights)
Try advanced models (LightGBM, CatBoost)
Deploy using Streamlit or Flask
Add real-time prediction interface

## 📌 Conclusion

This project demonstrates a complete machine learning pipeline for churn prediction with consistent performance across multiple models, making it a strong foundation for real-world business applications.
