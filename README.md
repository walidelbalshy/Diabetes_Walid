# Diabetes_Walid
---

## ✨ Project Overview

This project focuses on analyzing a medical dataset related to diabetes to identify key health indicators that contribute to the diagnosis of the disease. The goal is to use data analysis techniques to extract insights and potentially build a model that can assist in early detection.

---

## 📊 The Dataset

The dataset used is the **Pima Indians Diabetes Dataset**, which contains medical data for 768 female patients of Pima Indian heritage. It includes the following features:

* Pregnancies
* Glucose
* BloodPressure
* SkinThickness
* Insulin
* BMI
* DiabetesPedigreeFunction
* Age
* Outcome (1 = diabetic, 0 = non-diabetic)

Each row represents a patient’s record with various diagnostic attributes and the final outcome (whether the patient has diabetes or not).

---

## 🚀 What's Inside? (Methodology)

1. **Data Cleaning:**

   * Checked for missing values and handled zero entries in columns like `Glucose`, `BloodPressure`, `SkinThickness`, and `BMI`.
   * Replaced zeroes with the column median where medically inappropriate.

2. **Exploratory Data Analysis (EDA):**

   * Used visualization tools to understand distributions and correlations.
   * Plotted histograms, correlation heatmaps, and boxplots to identify patterns and outliers.

3. **Feature Scaling & Engineering:**

   * Normalized numerical features for better model performance.

4. **Model Building:**

   * Applied classification models including:

     * Logistic Regression
     * Decision Tree
     * Random Forest
     * K-Nearest Neighbors (KNN)
   * Evaluated model performance using accuracy, precision, recall, and F1 score.

---

## 💡 Key Findings & Insights

* **Glucose, BMI, and Age** are strongly associated with diabetes diagnosis.
* The dataset had several medically implausible zero values that required careful preprocessing.
* The **Random Forest model** performed best, achieving an accuracy of approximately **77%**.
* Feature importance analysis revealed that **Glucose** is the most significant predictor among all features.

---

## 🛠️ Technologies & Libraries Used

* **Python**
* **Pandas** for data manipulation
* **Matplotlib & Seaborn** for visualization
* **Scikit-learn** for model building and evaluation
* **Jupyter Notebook** for development and presentation

---
