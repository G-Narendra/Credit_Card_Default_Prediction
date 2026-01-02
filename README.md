# 💳 Credit Card Default Prediction
### Financial Risk Assessment & Machine Learning Pipeline

<p align="center">
<img src="https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/Scikit--Learn-Classification-F7931E?style=for-the-badge&logo=scikitlearn">
<img src="https://img.shields.io/badge/XGBoost-Risk%20Modeling-2EAD33?style=for-the-badge">
<img src="https://img.shields.io/badge/FinTech-Default%20Prediction-green?style=for-the-badge">
<img src="https://img.shields.io/badge/Metrics-ROC--AUC-8E44AD?style=for-the-badge">
</p>

---

## 🌟 Overview

Credit card default is a significant challenge for financial institutions, leading to substantial monetary losses. This project implements a **Supervised Machine Learning** system designed to predict the likelihood of a customer defaulting on their next payment. By analyzing historical payment behavior, credit limits, and demographic data, the model provides a data-driven risk score to help banks minimize credit risk.



---

## 🎯 Key Features

* ✅ **Risk Assessment:** Predicts the probability of default to categorize customers into risk tiers.
* ✅ **Financial Data Engineering:** Robust preprocessing of historical bill amounts and payment statuses.
* ✅ **Multi-Model Benchmark:** Comparative analysis of Logistic Regression, Decision Trees, Random Forest, and XGBoost.
* ✅ **High-Fidelity Evaluation:** Prioritizes **Recall** and **ROC-AUC** to ensure the model effectively identifies potential defaulters (minimizing False Negatives).

---

## 🧠 Tech Stack

| Category | Tools |
| :--- | :--- |
| **Language** | Python 3.8+ |
| **ML Framework** | Scikit-learn, XGBoost |
| **Data Analysis** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |
| **Environment** | Jupyter Notebook |

---

## 📁 Project Structure

```bash
Credit_Card_Default_Prediction/
├── src/
│   └── Credit_Card_Default_Prediction.ipynb    # Main pipeline: cleaning, training, & metrics
├── docs/
│   ├── Intro.txt                               # Project context & objectives
│   └── Report.txt                              # Detailed performance & model insights
├── requirements.txt                            # Dependencies
└── README.md                                   # Documentation

```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone [https://github.com/G-Narendra/Credit_Card_Default_Prediction.git](https://github.com/G-Narendra/Credit_Card_Default_Prediction.git)
cd Credit_Card_Default_Prediction

```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt

```

### 3️⃣ Run the Notebook

```bash
jupyter notebook Credit_Card_Default_Prediction.ipynb

```

---

## 📊 Methodology & Evaluation

### Data Preprocessing

The model analyzes critical credit-related features including:

* **PAY_0 to PAY_6:** History of past monthly payment records (delay status).
* **BILL_AMT:** Amount of bill statement per month.
* **PAY_AMT:** Amount of previous payment.
* **Demographics:** Age, Education, Marriage status, and Sex.

### Model Comparison

The project evaluates various classifiers to determine which algorithm best captures the non-linear nature of financial distress:

* **Logistic Regression:** For baseline linear interpretability.
* **Ensemble Methods:** Random Forest and XGBoost to handle complex interactions between payment delays and balance-to-limit ratios.

---

## 🚀 Future Roadmap

* [ ] **Technical Indicator Integration:** Adding credit utilization ratios as a primary feature.
* [ ] **Deep Learning:** Implementing an Artificial Neural Network (ANN) for deeper pattern recognition.
* [ ] **Deployment:** Creating a real-time dashboard using Streamlit for credit risk visualization.

---

## 👨‍💻 Author

**Narendra (G‑Narendra)** AI | ML | Python | Full Stack | GenAI Enthusiast

📧 [Email Me](mailto:narendragandikota2540@gmail.com) | 💼 [LinkedIn](https://linkedin.com/in/g-narendra/) | 👨‍💻 [GitHub](https://github.com/G-Narendra)

---

<p align="center">⭐ If you find this project useful, feel free to give it a star! 🚀</p>
