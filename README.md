# 🏡 House Price Prediction using Machine Learning

##  Project Overview

This project focuses on building an **end-to-end regression pipeline** to predict house prices using machine learning techniques. The goal is to demonstrate the complete data science workflow — from data preprocessing and exploratory data analysis (EDA) to feature engineering, model training, and evaluation.

---

## 📂 Dataset

* Dataset contains residential housing data with numerical and categorical features
* Target variable: **SalePrice**
* Common challenges addressed:

  * Missing values
  * Skewed target distribution
  * Categorical feature handling

---

## 🔍 Exploratory Data Analysis (EDA)

* Analyzed the distribution of `SalePrice` and applied transformation to handle skewness
* Studied relationships between important features and house prices
* Identified key variables influencing price such as area, number of bathrooms, and house age

---

## 🛠️ Data Preprocessing

A robust preprocessing pipeline was implemented:

* Handled missing values using appropriate statistical methods
* Encoded categorical variables correctly
* Scaled numerical features where required
* Ensured the pipeline was reusable and model-agnostic

---

## 🧠 Feature Engineering

Created new features to improve predictive performance:

* **TotalSF** – Total square footage of the house
* **TotalBath** – Total number of bathrooms
* **Age** – Age of the house at the time of sale

These engineered features added meaningful information beyond the raw dataset.

---

## 🤖 Model Building

Two regression models were trained and compared:

1. **Linear Regression** – Baseline model
2. **XGBoost Regressor** – Advanced ensemble model

XGBoost demonstrated superior performance compared to the linear baseline.

---

## 📊 Model Evaluation

* Evaluated models using standard regression metrics
* Compared performance to select the best-performing model
* Generated final predictions and prepared a submission file

---

## 🚀 Results

* XGBoost outperformed Linear Regression
* Feature engineering significantly improved model accuracy
* End-to-end pipeline ensured clean, reproducible modeling

---

## 🔮 Future Enhancements

* Hyperparameter tuning using **GridSearchCV** or **RandomizedSearchCV**
* Advanced feature engineering with interaction terms
* Ensemble modeling to further improve prediction accuracy

---

## 🧰 Tools & Technologies

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* XGBoost

---

## 📌 Conclusion

This project demonstrates a complete machine learning workflow for a real-world regression problem. It highlights strong skills in data preprocessing, feature engineering, model comparison, and evaluation.

---

⭐ If you find this project useful, feel free to star the repository!
