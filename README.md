# Credit Card Fraud Detection 🛡️

This project demonstrates how to detect fraudulent transactions using machine learning on the popular [Kaggle Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). The focus is on handling class imbalance using **undersampling** and comparing the performance of multiple classifiers.

---

## 📁 Dataset

- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Transactions made by European cardholders in September 2013.
- Contains **284,807 rows** with **492 fraud cases (0.17%)**.

---

## 🧠 Models Used

- **Decision Tree**
- **Random Forest**
- **Gradient Boosting**

Each model is tuned with `GridSearchCV` and evaluated using:

- ROC AUC Score
- F1 Score
- Precision
- Recall

---

## ⚙️ Techniques Applied

- ✅ StandardScaler normalization on `Time` and `Amount` features  
- ✅ Undersampling to handle class imbalance  
- ✅ Hyperparameter tuning via Grid Search  
- ✅ Feature importance visualization  
- ✅ Model comparison with a formatted table and bar chart  
