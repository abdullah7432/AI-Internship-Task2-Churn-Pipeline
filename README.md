# AI Internship Task 2 - Churn Prediction Pipeline

## 📊 Project Overview
This project is part of an AI Internship Task 2.  
The goal is to build a machine learning pipeline to predict customer churn using the Telco Customer Churn dataset.

The model is trained using machine learning techniques and saved as a pipeline using Joblib for future predictions.

---

## 📁 Files in this Repository
- `news-topic-classifier-bert(ML).ipynb` → Jupyter Notebook (Model training & analysis)
- `churn_pipeline.pkl` → Trained ML model pipeline (saved using joblib)
- `Telco-Customer-Churn.csv` → Dataset used for training

---

## ⚙️ Workflow Steps
1. Data Loading
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Model Training
6. Model Evaluation
7. Saving Model using Joblib

---

## 🤖 Machine Learning Model
- Algorithm: (Mention your model here e.g. Random Forest / Logistic Regression)
- Library: Scikit-learn
- Output: Churn Prediction (Yes/No)

---

## 💾 Model Saving
The trained model pipeline is saved using Joblib:

```python
import joblib
joblib.dump(model, "churn_pipeline.pkl")
