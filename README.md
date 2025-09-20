# Customer Churn Prediction 📊

## 📌 Project Overview
Customer churn is when customers stop doing business with a company.  
Predicting churn is critical for telecom, banks, and SaaS companies to retain customers.  

In this project, we use the **Telco Customer Churn dataset** to build and evaluate machine learning models that predict whether a customer will churn.

---

## 📂 Dataset
- Dataset: [Telco Customer Churn (Kaggle)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
- File: `WA_Fn-UseC_-Telco-Customer-Churn.csv`  

The dataset includes customer demographics, account information, services subscribed, and churn label (`Yes`/`No`).

---

## 🔧 Steps in the Project
1. Data Cleaning & Preprocessing (handling missing values, encoding categorical variables).  
2. Feature Scaling using `StandardScaler`.  
3. Model Training:
   - Logistic Regression  
   - Random Forest  
   - XGBoost  
4. Evaluation using:
   - Accuracy  
   - F1-score  
   - Confusion Matrix  
5. Feature Importance Visualization.

---

## 🧑‍💻 Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib, Seaborn  

---

## 📊 Results

We trained **three models** to predict customer churn.  

| Model                | Accuracy | F1-Score |
|-----------------------|----------|----------|
| Logistic Regression  | ~80%     | ~0.62    |
| Random Forest        | ~85%     | ~0.67    |
| XGBoost              | ~86%     | ~0.68    |

✅ **Best Model:** XGBoost (highest accuracy and F1-score).  

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/your-username/customer-churn-prediction.git
cd customer-churn-prediction

# Install dependencies
pip install -r requirements.txt

# Open notebook
jupyter notebook notebooks/churn_prediction.ipynb
