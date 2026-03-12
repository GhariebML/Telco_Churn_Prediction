# 📊 Telco Customer Churn Prediction

<div align="center">

**End-to-End Machine Learning Project**

[![Python](https://img.shields.io/badge/Python-3.8+-blue?style=flat-square&logo=python)](https://python.org)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange?style=flat-square&logo=scikit-learn)](https://scikit-learn.org)
[![XGBoost](https://img.shields.io/badge/XGBoost-Gradient%20Boosting-green?style=flat-square)](https://xgboost.readthedocs.io)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat-square&logo=jupyter)](https://jupyter.org)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](LICENSE)

*Predicting customer churn in telecom using EDA, Feature Engineering & ML classification models*

</div>

---

## 🚀 Project Overview

Customer churn is a major business challenge for telecom companies — retaining existing customers is significantly cheaper than acquiring new ones. This end-to-end project builds a machine learning pipeline to identify customers likely to churn, enabling proactive retention strategies.

**The project covers the complete ML workflow:**
- Data cleaning & preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model training, tuning & evaluation
- Business insights extraction

---

## 📂 Dataset

**IBM Telco Customer Churn Dataset** — 7,043 customers, 21 features

| Feature Category | Examples |
|---|---|
| Demographics | Gender, Senior Citizen, Partner, Dependents |
| Account Info | Tenure, Contract Type, Billing Method |
| Services | Internet, Phone, Streaming, Security |
| Charges | Monthly Charges, Total Charges |
| **Target** | **Churn (Yes/No)** |

---

## 🧹 Data Preprocessing

- Handled missing values in `TotalCharges`
- Encoded categorical variables (Label + One-Hot Encoding)
- Scaled numerical features with `StandardScaler`
- Applied train-test split (80/20) to prevent data leakage

---

## 📊 EDA — Key Insights

| Finding | Insight |
|---|---|
| Contract Type | Month-to-month customers churn the most |
| Tenure | Short-tenure customers are highest risk |
| Monthly Charges | Higher charges correlate with churn |
| Internet Service | Fiber optic users churn more than DSL |
| Payment Method | Electronic check users churn more |

---

## 🤖 Machine Learning Models

| Model | Accuracy | Precision | Recall | F1-Score | AUC-ROC |
|---|---|---|---|---|---|
| Logistic Regression | ~80% | ~67% | ~56% | ~61% | ~84% |
| Random Forest | ~79% | ~65% | ~48% | ~55% | ~83% |
| **XGBoost** | **~81%** | **~68%** | **~58%** | **~63%** | **~86%** |

> XGBoost achieved the best overall performance with highest AUC-ROC score.

---

## 🧠 Key Business Findings

- **Contract type** is the strongest churn predictor
- **Tenure** significantly reduces churn probability
- **Fiber optic** and **electronic check** customers are highest risk
- **Automatic payment** is associated with lower churn rates
- Pricing strategy (monthly charges) directly impacts retention

---

## 🛠️ Technologies Used

```
Python | Pandas | NumPy | Scikit-learn | XGBoost
Matplotlib | Seaborn | Jupyter Notebook
```

---

## 👤 Author

<div align="center">

**Mohamed Gharieb** — *Data Scientist & ML Engineer*

[![GitHub](https://img.shields.io/badge/GitHub-GhariebML-181717?style=flat-square&logo=github)](https://github.com/GhariebML)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ghariebml-007BB5?style=flat-square&logo=linkedin)](https://linkedin.com/in/ghariebml)

</div>

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.
