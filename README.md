#  Heart Disease Prediction using Machine Learning

This project uses the **Cleaned Heart Disease Dataset** to predict whether a person is likely to develop heart disease based on clinical features such as age, blood pressure, cholesterol, thalassemia, chest pain type, and more.

Two models were developed and compared:
- 🔹 **Logistic Regression**
- 🔸 **Random Forest Classifier**

---

## 📊 Features of the Project

- ✅ Cleaned and structured dataset (no missing values)
- 📈 Exploratory Data Analysis (EDA)
- 🧠 Machine Learning model training & evaluation
- 🧪 Confusion matrices, classification reports, and accuracy comparison
- 📉 Visualizations: heatmaps, countplots, bar charts
- 📌 Final conclusion & technical interpretation
- 📄 Export-ready report (PDF)

---

## 🔬 Dataset Overview

- **Source:** Cleaned version of the Merged Heart Dataset
- **Target column:** `target` (1 = heart disease present, 0 = not present)
- **Observations:** 1000+
- **Features include:** age, sex, cp, trestbps, chol, fbs, restecg, thalachh, exang, oldpeak, slope, ca, thal

---

## 📊 Model Performance

| Model               | Accuracy  |
|---------------------|-----------|
| Logistic Regression | 72.49%    |
| Random Forest       | 96.56% ✅ |

> 🔥 **Random Forest outperformed Logistic Regression** and provided strong predictive performance with meaningful clinical insights.

---

## 🎯 What We Learned

From both model training and visual analysis, we found that:

- Features like `cp` (chest pain), `oldpeak`, `thalachh`, `ca`, and `thal` were strongly associated with heart disease.
- Random Forest could model **non-linear relationships** and detect subtle patterns better than Logistic Regression.
- Our model not only performs well statistically, but aligns with **real-world cardiology logic**.

---

## 📁 Files in the Repo

- `heart-disease-prediction.ipynb` – Source Jupyter Notebook
- `heart.csv` – Cleaned dataset
- `heart-disease-report.pdf` – Final formatted report (ready for sharing)
- `requirements.txt` – Required libraries
- `README.md` – Project overview (this file)

---

## 📌 Future Work

- 🔍 Hyperparameter tuning (GridSearchCV)
- 🧠 SHAP/LIME explainability
- 🌐 Deploy using Streamlit as a diagnostic tool
- 📊 Integrate more patient hist

## 👨‍💻 Author

Developed by **Azib Malick**  
© 2025 Azib Malick. All rights reserved.

---

⭐ **If you found this useful, consider giving the repo a star!**
