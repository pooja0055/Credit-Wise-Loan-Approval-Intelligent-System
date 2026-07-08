# 💳 CreditWise — Intelligent Loan Approval System

> A Machine Learning powered system that predicts loan approval outcomes using **Linear Regression, Logistic Regression, KNN, and Naive Bayes**, helping financial institutions make faster, data-driven, and unbiased lending decisions.

![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)

---

## 📖 Overview

**CreditWise** is an end-to-end Machine Learning project that analyzes applicant financial and demographic data to predict whether a loan should be **approved or rejected**. The project compares multiple ML algorithms to identify the most reliable model for real-world credit risk assessment.

This system can help banks, NBFCs, and fintech platforms:
- ⚡ Speed up loan approval decisions
- 📉 Reduce default risk through data-backed predictions
- ⚖️ Minimize human bias in credit decisions
- 📊 Gain insights into which factors most influence approval

---

## 🧠 Models Implemented

| Model | Type | Purpose in this Project |
|---|---|---|
| **Linear Regression** | Regression | Predicting continuous credit-related metrics (e.g., loan amount / risk score) |
| **Logistic Regression** | Classification | Predicting binary loan approval outcome (Approved / Rejected) |
| **K-Nearest Neighbors (KNN)** | Classification | Similarity-based approval prediction |
| **Naive Bayes** | Classification | Probabilistic approval prediction based on applicant features |

Each model is trained, evaluated, and compared to select the **best performing algorithm** for deployment.

---

## 🚀 Features

- 🔍 Exploratory Data Analysis (EDA) with visualizations
- 🧹 Data preprocessing (missing value handling, encoding, scaling)
- 🤖 Multiple ML model training & comparison
- 📈 Model evaluation using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix
- 📊 Visual performance comparison across all four algorithms
- 💡 Feature importance / correlation analysis
- 🧪 Easily extensible to add new models or datasets

---

## 🗂️ Project Structure

```
CreditWise-Loan-Approval-System/
│
├── data/
│   └── loan_data.csv                 # Dataset used for training/testing
│
├── notebooks/
│   └── CreditWise_Analysis.ipynb     # Main analysis & model building notebook
│
├── src/
│   ├── __init__.py
│   ├── preprocessing.py              # Data cleaning & feature engineering
│   ├── train_models.py               # Model training scripts
│   └── evaluate.py                   # Model evaluation & metrics
│
├── models/
│   └── saved_models/                 # Serialized trained models (.pkl)
│
├── images/
│   └── results/                      # Charts & visualizations
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```
---

## 📊 Dataset

- **Source:** `[e.g., Kaggle - Loan Prediction Dataset / Custom dataset]`
- **Records:** `[e.g., 5000 applicants]`
- **Features:** `[e.g., Income, Credit History, Loan Amount, Education, Employment Type, Marital Status, etc.]`
- **Target Variable:** `Loan_Status` (Approved / Rejected)

---

## ⚙️ Installation & Setup

1. **Clone the repository**
```bash
git clone https://github.com/<your-username>/CreditWise-Loan-Approval-System.git
cd CreditWise-Loan-Approval-System
```

2. **Create a virtual environment (recommended)**
```bash
python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Run the notebook or script**
```bash
jupyter notebook notebooks/CreditWise_Analysis.ipynb
```
or
```bash
python src/train_models.py
```

---

## 📈 Model Performance

| Model | Accuracy | Precision | Recall | F1-Score |
|---|---|---|---|---|
| Logistic Regression | `0.88` | `0.78` | `0.83` | ` 0.80` |
| KNN | `0.88` | `0.78` | ` 0.83` | ` 0.80` |
| Naive Bayes | `0.86` | `0.81` | `0.70` | `0.75` |



**🏆 Best Performing Model:** `[Naive Bayes]`


---

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook / VS Code

---

## 🔮 Future Enhancements

- [ ] Add ensemble models (Random Forest, XGBoost) for improved accuracy
- [ ] Deploy as a web app using Flask/Streamlit
- [ ] Add SHAP/LIME for model explainability
- [ ] Integrate with a real-time loan application form
- [ ] Hyperparameter tuning with GridSearchCV


---

## 👤 Author

**[Pooja Dewangan]**
- GitHub: [@pooja0055](https://github.com/pooja0055)
- LinkedIn: [poojadewangan](https://in.linkedin.com/in/pooja-dewangan-71724a344)
- Email: poojadewangan0505@gmail.com

---


