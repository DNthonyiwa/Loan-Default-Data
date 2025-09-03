# Loan Default Prediction 📊💳

This project builds and evaluates machine learning models to predict **loan defaults** using historical loan and customer data.  
The goal is to help financial institutions minimize risk, reduce losses, and improve decision-making in credit approval.

---

## 🚀 Project Overview
- **Data Source:** `Task 3 and 4_Loan_Data.csv`
- **Objective:** Predict whether a customer will default on a loan.
- **Key Business Goal:** Maximize recall (catch all potential defaulters) to avoid financial losses.

---

## 🔧 Tools & Libraries
- **Python** (Pandas, NumPy)
- **Matplotlib & Seaborn** → Visualization
- **Scikit-learn** → Logistic Regression, Decision Trees, Random Forest
- **Imbalanced-learn** → Over-sampling & under-sampling
- **Evaluation Metrics** → Accuracy, Recall, Precision, Confusion Matrix

---

## 📈 Methodology
1. **Exploratory Data Analysis (EDA):**
   - Distribution of defaults
   - Boxplots to compare financial variables against default behavior
   - Class imbalance check
2. **Model Training:**
   - Logistic Regression
   - Decision Tree
   - Random Forest
3. **Handling Imbalance:**
   - Random Over-Sampling
   - Random Under-Sampling
4. **Evaluation:**
   - Confusion Matrix
   - Accuracy, Precision, Recall
   - Business impact assessment

---

## ✅ Results & Insights
- **Recall (Sensitivity): 100%**
  - No false negatives (no missed defaulters)
  - Prevented major financial losses
- **Precision: 99.4%**
  - Very few false positives (only 2 good customers wrongly flagged)
- **Accuracy: ~99.9%**
  - Extremely strong overall performance
- **Financial Impact:**
  - Correctly flagged 348 defaulters
  - Estimated savings: **$3.48M**
  - Opportunity cost: 2 rejected good applications (minimal)

---

## 🏦 Business Recommendations
1. **Immediate Deployment** – The model’s performance is exceptional.
2. **Manual Review for False Positives** – Add human oversight for borderline cases.
3. **Monitor Performance** – Track recall/precision over time to ensure stability.
4. **Risk Management** – Model slightly conservative, which is excellent for minimizing financial risk.

---

## 📊 Example Visualization
Class distribution before balancing:

![Class Balance](images/class_balance.png)

---

## 📌 Future Work
- Incorporate more advanced models (XGBoost, Gradient Boosting, Neural Nets).
- Perform feature engineering to extract deeper customer insights.
- Deploy as an API for integration with loan management systems.

---

## 💡 Key Takeaway
This project demonstrates how machine learning can provide **real financial value** in banking:
- **Zero losses from undetected defaulters**
- **Millions saved in prevented defaults**
- **High confidence in loan approval decisions**

---
