# 🔥 Employee Burnout Analysis & Prediction

This repository presents an end-to-end data science project that analyzes and predicts employee burnout levels using exploratory data analysis, feature engineering, and machine learning models. The goal is to gain insights into factors contributing to burnout and build predictive models using PCA and ensemble learning techniques.

## 📁 Project Structure

- `employee_burnout_analysis.csv` – Raw dataset containing employee attributes and burnout metrics.
- `Code.txt` – Complete Python notebook/script used for data analysis, visualization, and modeling.
- `README.md` – Project documentation.

---

## 📊 Problem Statement

With rising work-from-home and hybrid environments, organizations are facing increased challenges in managing employee well-being. This project aims to:

- Analyze demographic, work-related, and mental fatigue data.
- Identify patterns and correlations associated with employee burnout.
- Build a predictive model to estimate the **Burn Rate** based on key features.

---

## 🔍 Exploratory Data Analysis

The following steps were conducted to explore the dataset:

- Checked for missing and duplicate values.
- Assessed skewness and feature distribution.
- Visualized gender, company type, and work-from-home (WFH) setups.
- Correlation heatmaps and line plots to uncover trends in burnout rates.

📌 **Key Visual Insights:**

- Gender and company type significantly influence burnout levels.
- Mental fatigue score and resource allocation are highly correlated with burn rate.
- Higher designation levels show differing burnout and fatigue trends.

---

## 🧠 Machine Learning Pipeline

### ✅ Feature Engineering

- Label encoding for categorical variables (`Gender`, `Company Type`, `WFH Setup Available`)
- Handled missing values using mean imputation
- Dropped irrelevant columns like `Employee ID`

### ✅ Dimensionality Reduction

- Applied **PCA (Principal Component Analysis)** to reduce feature space while retaining 95% of variance

### ✅ Model Building

Two ensemble regressors were implemented:

1. **Random Forest Regressor**
   - Train Accuracy: ~99.8%
   - Test Accuracy: ~86.6%

2. **AdaBoost Regressor**
   - Train Accuracy: ~86.7%
   - Test Accuracy: ~84.1%

*Note: R² Score used to evaluate model performance.*

---

## ⚙️ Tools & Libraries Used

- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Plotly)
- **Scikit-learn** (LabelEncoder, PCA, Train-Test Split, RandomForestRegressor, AdaBoostRegressor)
- **Google Colab** – Cloud notebook environment for execution

---

## 📈 Conclusion

This project demonstrates how burnout levels can be predicted using demographic and workplace-related features. Ensemble models, particularly Random Forest, achieved high accuracy and offer explainable insights into what affects burnout the most.

---



This project is licensed under the MIT License.

---

⭐ **If you found this helpful, please give it a star!**
