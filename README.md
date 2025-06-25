# Customer Churn Prediction

This project analyzes bank customer data and predicts customer churn using machine learning (Random Forest). It includes EDA, data cleaning, visualization, and model evaluation.

## 📁 Dataset
- Source: Provided CSV (`Churn_Modelling.csv`)
- Columns: Age, Gender, Geography, Balance, Estimated Salary, etc.
- Target: `Exited` (1 = churned, 0 = stayed)

## 📊 Features
- Data Cleaning & Encoding
- Exploratory Data Analysis (EDA)
- Advanced Visualization with Seaborn & Matplotlib
- Model Training with RandomForestClassifier
- Performance Metrics (Accuracy, Confusion Matrix, F1-Score)

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib

## 🧪 How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/churn_analysis_and_model.ipynb
