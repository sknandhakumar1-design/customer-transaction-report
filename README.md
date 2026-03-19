# 💳 Customer Transaction Prediction

![Python](https://img.shields.io/badge/Python-3.x-blue)
![ML](https://img.shields.io/badge/Machine%20Learning-Classification-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Project Overview
This project builds a Machine Learning model to predict whether a customer
will make a transaction in the future. The dataset contains 200 anonymized
numerical features per customer. The goal is to identify potential buyers
to help banks and financial institutions target the right customers.

---

## 🎯 Project Goals
- Predict if a customer will make a transaction (Binary Classification)
- Compare multiple ML models to find the best performer
- Evaluate using ROC-AUC, Precision, Recall, and F1 Score

---

## 📂 Dataset
- **Total Records:** 2,00,000 customers
- **Features:** 200 anonymized numerical variables (var_0 to var_199)
- **Target:** 1 = Will transact, 0 = Will not transact

---

## 🔧 Tech Stack
- **Language:** Python 3.x
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost
- **Environment:** Jupyter Notebook

---

## 🤖 Models Trained & Compared
| Model | Performance |
|-------|------------|
| Logistic Regression | Baseline model |
| Random Forest | Handles high dimensions well |
| XGBoost | ✅ Best performing model |

**XGBoost is recommended for production deployment.**

---

## ⚠️ Challenges & Solutions
| Challenge | Solution |
|-----------|----------|
| 200 anonymized features — no domain interpretation | Used tree-based models |
| High dimensional data | Applied regularization & depth control |
| Class imbalance risk | Used ROC-AUC as evaluation metric |
| Overfitting risk | Avoided unnecessary feature engineering |

---

## 💡 Conclusion
- Successfully built a customer transaction prediction system
- Compared multiple ML models
- XGBoost performed best and is recommended for production
- Model helps banks identify customers likely to transact in future

---

## 📁 Project Structure
```
customer-transaction-report/
├── Customer Transaction Report.ipynb
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run
1. Clone the repository
```bash
git clone https://github.com/sknandhakumar1-design/customer-transaction-report.git
```
2. Install dependencies
```bash
pip install -r requirements.txt
```
3. Open Jupyter Notebook
```bash
jupyter notebook "Customer Transaction Report.ipynb"
```

---

## 👤 Author
**Nandha Kumar S K**
- Intern @ DataMites
- GitHub: [@sknandhakumar1-design](https://github.com/sknandhakumar1-design)
