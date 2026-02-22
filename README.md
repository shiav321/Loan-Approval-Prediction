# 🏦 Loan Approval Prediction Bot

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

**An end-to-end Machine Learning system that predicts whether a loan application will be approved or rejected — with 96% accuracy.**

</div>

---

## 📌 Problem Statement

Banks process thousands of loan applications daily. Manual review is slow, inconsistent, and expensive. This project automates the loan approval decision using machine learning — making the process faster, fairer, and more accurate.

---

## 🎯 Results

| Metric | Score |
|--------|-------|
| ✅ Accuracy | **96%** |
| 📊 Precision | 94% |
| 📈 Recall | 95% |
| 🔷 ROC-AUC | 0.97 |

---

## 🧠 How It Works

```
Raw Loan Data → Data Cleaning → Feature Engineering → ML Model → Prediction → Web App
```

1. **Data Collection** — Customer demographics, income, credit history, loan amount
2. **Preprocessing** — Handled missing values, encoded categorical variables, scaled features
3. **Model Training** — Compared Logistic Regression, Decision Tree, Random Forest, XGBoost
4. **Best Model** — Random Forest Classifier (96% accuracy)
5. **Deployment** — Live Streamlit web app for real-time predictions

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|-----------|
| Language | Python 3.8+ |
| ML Library | Scikit-learn |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Web App | Streamlit |
| Deployment | Heroku |

---

## 📂 Project Structure

```
Loan-Approval-Prediction/
│
├── 📓 loan_approval.ipynb       # Main Jupyter notebook (EDA + Model training)
├── 🐍 app.py                    # Streamlit web application
├── 📊 loan_data.csv             # Dataset
├── 🤖 model.pkl                 # Saved trained model
├── 📋 requirements.txt          # Dependencies
└── 📖 README.md                 # Project documentation
```

---

## 🚀 How to Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/shiav321/Loan-Approval-Prediction.git
cd Loan-Approval-Prediction

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the Streamlit app
streamlit run app.py
```

---

## 📊 Features Used

- Applicant Income
- Co-applicant Income  
- Loan Amount & Loan Term
- Credit History
- Property Area (Urban/Rural/Semi-urban)
- Education & Employment Status
- Gender & Marital Status

---

## 📈 Model Comparison

| Model | Accuracy |
|-------|----------|
| Logistic Regression | 80% |
| Decision Tree | 85% |
| Random Forest | **96%** ✅ |
| XGBoost | 93% |

---

## 👨‍💻 About the Developer

**Shiva Keshava** — B.Tech AI & Data Science Graduate

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/shiva-keshava-b71355364)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-FF6B6B?style=flat&logo=google-chrome)](https://shivaprofilewebsite.lovable.app/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat&logo=github)](https://github.com/shiav321)

---

<div align="center">
⭐ If you found this project helpful, please give it a star!
</div>
