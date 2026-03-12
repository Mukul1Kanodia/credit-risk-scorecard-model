# credit-risk-scorecard-model

**Predicting Loan Default Probability using Machine Learning**

---

## Project Overview
Built an end-to-end credit risk scorecard model on 123,000+ real Lending Club loans 
to predict the probability of default. Compared Logistic Regression and XGBoost, 
performed risk tier segmentation, and delivered findings in a business memo format 
replicating a real analyst workflow.

---

## Key Results
| Model | AUC-ROC | Accuracy | Recall |
|---|---|---|---|
| XGBoost | 0.72 | 81% | 98% |
| Logistic Regression | 0.70 | 65% | 66% |

---

## Risk Tier Segmentation
Borrowers segmented into three tiers using predicted default probability:
- 🟢 **Low Risk** (0–30% probability) — lowest realized default rate
- 🟡 **Medium Risk** (30–60% probability) — moderate default rate
- 🔴 **High Risk** (60–100% probability) — highest realized default rate

---

## Project Structure
- `notebook/` — Full annotated Jupyter notebook
- `memo/` — One-page business memo summarizing findings
- `outputs/` — ROC curve, feature importance chart, risk tier visualization

---

## Tools & Libraries
Python, pandas, NumPy, scikit-learn, XGBoost, Matplotlib, Google Colab

---

## Key Learnings
- Identified and resolved critical data leakage (target variable with 0.84 feature importance)
- Applied StandardScaler to improve Logistic Regression AUC from 0.68 → 0.70
- Engineered 8+ features including loan-to-income ratio, credit age, and utilization flags

---

## Dataset
[Lending Club Loan Data — Kaggle](https://www.kaggle.com/datasets/wordsforthewise/lending-club)
```

---

