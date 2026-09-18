# 🕵️ Fraud Detection ML Project

> **End-to-End Machine Learning System for Financial Fraud Detection**  
> Achieved **94% Detection Accuracy** with Random Forest & XGBoost

![Python](https://img.shields.io/badge/Python-3.9+-blue?style=for-the-badge&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-0.99_AUC-green?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Streamlit-Deployed-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Accuracy](https://img.shields.io/badge/Accuracy-94%25-brightgreen?style=for-the-badge)

---

## 📌 About the Project

A complete **end-to-end Machine Learning pipeline** for detecting fraudulent financial transactions. The system handles highly imbalanced datasets, trains and compares multiple ML models, and deploys a real-time prediction interface using **Streamlit** — all in Python.

This project simulates a real-world fraud detection system used by banks and fintech companies to protect customers from unauthorized transactions.

---

## 🎯 Business Problem

Financial fraud costs billions of dollars globally every year. Traditional rule-based systems miss sophisticated fraud patterns. This ML-powered system:

- Automatically learns fraud patterns from historical data
- Detects fraudulent transactions in real-time
- Handles **heavily imbalanced datasets** (fraud is rare — <1% of transactions)
- Provides interpretable results for business decision-making

---

## ✨ Features

- ✅ **End-to-end ML Pipeline** — Data → Preprocessing → Training → Evaluation → Deployment
- ✅ **Imbalanced Dataset Handling** — Techniques for rare fraud class detection
- ✅ **Multiple ML Models** — Logistic Regression, Random Forest, XGBoost compared
- ✅ **Saved Pipeline** — `.pkl` model ready for production deployment
- ✅ **Streamlit App** — Interactive real-time fraud prediction interface
- ✅ **Comprehensive Evaluation** — Accuracy, Precision, Recall, F1, AUC-ROC
- ✅ **Visual Analysis** — Confusion Matrix, ROC Curve, Feature Importance

---

## 📊 Model Performance

| Model | Accuracy | AUC Score |
|---|---|---|
| Logistic Regression | Baseline | — |
| **Random Forest** | **98.7%** | — |
| **XGBoost** | — | **0.99** |
| **Overall Detection** | **94%** | — |

> 🏆 **Best Model: Random Forest** with 98.7% accuracy & XGBoost with 0.99 AUC

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **Python 3.9+** | Core programming language |
| **Pandas & NumPy** | Data manipulation & numerical operations |
| **Scikit-learn** | ML models, preprocessing & evaluation |
| **XGBoost** | Gradient boosting model |
| **Matplotlib & Seaborn** | Data visualization |
| **Streamlit** | Interactive web app deployment |
| **Pickle (.pkl)** | Model serialization & saving |
| **Jupyter Notebook** | Analysis & experimentation |

---

## 📁 Project Structure

```
fraud-detection-ml-project/
│
├── analyse_model.ipynb              # Main analysis & training notebook
├── fraud_detection.py               # Streamlit app for real-time prediction
├── fraud_detection_pipline.pkl      # Saved ML pipeline (production ready)
├── Streamlit output 1.pdf           # Streamlit app screenshot — normal transaction
├── Streamlit output 2.pdf           # Streamlit app screenshot — fraud detected
├── .gitignore                       # Git ignore file
├── LICENSE                          # MIT License
└── README.md                        # Project documentation
```

---

## 🔬 How It Works

```
Raw Transaction Data
        ↓
Data Preprocessing
  → Handle missing values
  → Feature engineering
  → Handle class imbalance
        ↓
Model Training & Comparison
  → Logistic Regression (baseline)
  → Random Forest
  → XGBoost
        ↓
Model Evaluation
  → Accuracy, Precision, Recall, F1
  → ROC-AUC Curve
  → Confusion Matrix
        ↓
Save Best Model → fraud_detection_pipline.pkl
        ↓
Streamlit App → Real-time Prediction
```

---

## 🚀 How to Run

### Step 1 — Clone Repository
```bash
git clone https://github.com/rakesh4407/fraud-detection-ml-project.git
cd fraud-detection-ml-project
```

### Step 2 — Install Dependencies
```bash
pip install pandas numpy scikit-learn xgboost matplotlib seaborn streamlit jupyter
```

### Step 3 — Run Analysis Notebook
```bash
jupyter notebook analyse_model.ipynb
```

### Step 4 — Launch Streamlit App
```bash
streamlit run fraud_detection.py
```

---

## 📸 App Screenshots

| Normal Transaction | Fraud Detected |
|---|---|
| See `Streamlit output 1.pdf` | See `Streamlit output 2.pdf` |

---

## 💡 Key Learnings

- 🔄 Handling **class imbalance** is critical in fraud detection
- 🌲 **Random Forest** outperforms Logistic Regression for complex fraud patterns
- 📈 **AUC-ROC** is a better metric than accuracy for imbalanced datasets
- ⚡ **XGBoost** achieves near-perfect AUC (0.99) for fraud classification
- 🚀 **Streamlit** enables rapid ML model deployment without web dev knowledge

---

## 👨‍💻 Author

**Jeremy Hayes**

Bachelor of Science, Software Engineering
Western Governor's University | Expected Graduation: December 2026
Dean's Award Recipient | IBM Certified Data Scientist

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rakesh%20G-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/rakesh-bca)
[![GitHub](https://img.shields.io/badge/GitHub-rakesh4407-181717?style=flat&logo=github)](https://github.com/rakesh4407)
[![Email](https://img.shields.io/badge/Email-rakee4407%40gmail.com-D14836?style=flat&logo=gmail)](mailto:rakee4407@gmail.com)

---

## 🏷️ Topics

`python` `machine-learning` `fraud-detection` `scikit-learn` `xgboost` `random-forest` `streamlit` `data-science` `classification` `imbalanced-dataset` `fintech` `jupyter-notebook`

---
