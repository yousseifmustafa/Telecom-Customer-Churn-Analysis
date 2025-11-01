
# 📊 Telecom Customer Churn Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-EDA-yellow?logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blueviolet?logo=matplotlib)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)
![Churn Accuracy](https://img.shields.io/badge/Accuracy-96%25-green)


## 👋 Overview

This project analyzes customer churn data for a telecom company. Using **Python**, we explore, visualize, and model the data to understand what drives customers to leave the service and how to predict it.

The goal is to identify important churn factors and build a machine learning model that can accurately predict whether a customer is likely to churn or not.

---

## 🧠 Objectives

- Understand the key factors behind customer churn
- Perform data cleaning and preprocessing
- Visualize insights through graphs
- Build and evaluate classification models to predict churn

---

## 🗃️ Dataset

The dataset contains various attributes about customers such as:

- Demographics (Age, Marital Status, Dependents)
- Services used (Internet, Tech Support, Streaming)
- Financial metrics (Monthly Charges, Long Distance Charges)
- Customer behaviors (Tenure, Referrals, Satisfaction)

---

## 🛠️ Tools & Libraries

- `pandas` – Data manipulation
- `matplotlib` & `seaborn` – Visualization
- `scikit-learn` – Machine learning models
- `numpy` – Numerical operations
- `LabelEncoder` – Categorical encoding
- `train_test_split`, `classification_report`, `confusion_matrix`, etc.

---

## 🔍 Exploratory Data Analysis (EDA)

Key analysis performed:

- Churn distribution and correlation heatmap
- Impact of age, internet type, premium support, and more
- Behavior of churn vs satisfaction level, contract offers, and support usage

📌 **Insights:**

- Customers without tech support or device protection are more likely to churn
- Younger users with low satisfaction scores tend to churn more
- Monthly charges and contract type are key indicators

---

## 🤖 Modeling

Several ML classifiers were tested including:

- **Logistic Regression**
- **GradientBoosting**
- **Random Forest**

The models were evaluated using:

- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**
- **Confusion Matrix**

✅ Best results were obtained from **Random Forest**, showing good balance between precision and recall.

---

## 📈 Results

| Model             | Accuracy | Precision | Recall | F1-score |
|------------------|----------|-----------|--------|----------|
| LogisticRegression | 95%      | 94%       | 86%    | 90%      |
| GradientBoosting     | 95%      | 94%       | 87%    | 90%      |
| Random Forest     | ✅ **96%**  | ✅ **97%**   | ✅ **86%**  | ✅ **91%**    |


---

## 📌 Conclusion

This project helped us:
- Identify key drivers of customer churn
- Build a solid predictive model
- Provide business insights to reduce churn rate

📣 Companies can focus on improving customer satisfaction and offering bundled services to retain their clients.

---

## 🚀 How to Run

1. Clone the repo:
```bash
git clone https://github.com/yousseifmustafa/Telecom-Customer-Churn-Analysis.git
```
2. Install requirements:
```bash
pip install -r requirements.txt
```
3. Run the Jupyter Notebook:
```bash
jupyter notebook telecom.ipynb
```

---

<div align="right">
    Made with ❤️ by <a href="https://github.com/yousseifmustafa">Yousseif Mustafa</a>
</div>
