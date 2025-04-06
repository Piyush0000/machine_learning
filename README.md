# ❤️ Predicting Heart Disease Using Machine Learning

This project explores the use of machine learning to predict the likelihood of a person having heart disease based on medical attributes.

---

## 📌 Problem Statement

> Given clinical parameters about a patient, can we predict whether or not they have heart disease?

---

## 📊 Dataset

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/heart+Disease)  
- **Kaggle Mirror**: [Heart Disease Classification Dataset](https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset)

---

## 🧠 ML Workflow

1. **Problem Definition**
2. **Data Collection & Cleaning**
3. **Exploratory Data Analysis (EDA)**
4. **Feature Engineering**
5. **Model Building (Scikit-learn)**
6. **Evaluation & Metrics**
7. **Model Export (Joblib)**

---

## 🔍 Features

| Feature | Description |
|--------|-------------|
| age | Age in years |
| sex | (1 = male; 0 = female) |
| cp | Chest pain type (0-3) |
| trestbps | Resting blood pressure |
| chol | Serum cholesterol |
| fbs | Fasting blood sugar |
| restecg | Resting ECG results |
| thalach | Max heart rate achieved |
| exang | Exercise-induced angina |
| oldpeak | ST depression |
| slope | Slope of peak exercise ST |
| ca | Major vessels colored |
| thal | Thalassemia (1, 3, 6, 7) |
| target | 1 = disease, 0 = no disease |

---

## 🛠 Tools Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Joblib (model export)

---

## 💾 Model Export

Trained model is saved as `heart_disease_model.pkl` and can be loaded using:

```python
import joblib
model = joblib.load("heart_disease_model.pkl")
