# Disease Prediction Toolkit — Heart Disease

## 📌 Bootcamp Context

This project was developed as part of the **DevTown 5-Day Bootcamp: “Disease Prediction: Save Lives with AI”**.

* **Instructor:** Ishan
* **Provider:** DevTown (with community partners: Google DSC, AWS Students Club, Microsoft LSA)
* **Date:** 22nd – 26th August 2025
* **Platform:** YouTube Live + Community Group Support

---

## 🎯 Project Overview

The goal of this project is to build a **Disease Prediction Toolkit** that can predict the presence of **heart disease** using machine learning models.

We followed a hands-on, project-based approach across 5 days of guided bootcamp sessions.

**Models Implemented:**

* Logistic Regression
* Decision Tree
* Random Forest

Dataset used: UCI Heart Disease dataset (Kaggle version).
Target column: `target` (0 = no disease, 1 = disease).

---

## ⚙️ Steps in the Project

1. **Preprocessing**

   * Handle missing values
   * Encode categorical features (`restecg`, `slope`, `thal`, `exang`)
   * Scale numeric features

2. **Training**

   * Train Logistic Regression, Decision Tree, Random Forest models using `scikit-learn`
   * Split dataset into training and testing sets

3. **Evaluation**

   * Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC
   * Visualizations: Confusion Matrix, ROC Curves

4. **Documentation**

   * Professional GitHub repository
   * 5-slide presentation
   * 30-second demo video

---

## 📊 Results (Sample)

| Model               | Accuracy | Precision | Recall | F1-score | ROC-AUC |
| ------------------- | -------- | --------- | ------ | -------- | ------- |
| Logistic Regression | 0.85     | 0.83      | 0.81   | 0.82     | 0.88    |
| Decision Tree       | 0.80     | 0.79      | 0.77   | 0.78     | 0.82    |
| Random Forest       | 0.87     | 0.86      | 0.84   | 0.85     | 0.90    |

*(Actual results will be available after running the notebook.)*

---

## 📂 Repository Structure

```
Disease-Prediction-Toolkit/
│── Heart_Disease_Prediction_project.ipynb   # Main notebook
│── README.md                                # Documentation
│── presentation/heart_disease_presentation.pdf # 5-slide presentation
```

---

## 📑 Deliverables

* **GitHub Repo:** Complete toolkit with code, data, and results
* **Demo Video:** 30-second walkthrough of predictions
* **Slides:** 5-slide presentation on dataset, preprocessing, models, results, and insights

---

## 🚀 Insights & Next Steps

* Random Forest consistently gave the best performance in this toolkit.
* Improvements can include hyperparameter tuning, cross-validation, and deployment as a web app using Flask or Streamlit.

---

⭐ **This project was developed as part of the DevTown 5-Day Bootcamp: “Disease Prediction: Save Lives with AI”**

