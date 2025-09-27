# Customer Churn Prediction 📊

## 📌 Project Overview
Customer churn occurs when customers stop doing business with a company.  
Predicting churn is critical for telecom, banking, and SaaS companies to retain customers and reduce revenue loss.

This project utilizes the **Telco Customer Churn dataset** to build and evaluate several machine learning models that predict whether a customer will churn.  
The goal is to identify at-risk customers and provide actionable insights for retention strategies.

---

## 📂 Dataset
- **Source:** [Telco Customer Churn (Kaggle)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
- **File:** `WA_Fn-UseC_-Telco-Customer-Churn.csv`  

The dataset includes:
- Customer demographics
- Account information
- Services subscribed
- Churn label (`Yes`/`No`)

---

## 🔧 Project Workflow
1. **Data Cleaning & Preprocessing:**  
   - Handle missing values, encode categorical variables.
2. **Feature Scaling:**  
   - Use `StandardScaler`.
3. **Model Training:**  
   - Logistic Regression  
   - Random Forest  
   - XGBoost  
4. **Evaluation Metrics:**  
   - Accuracy  
   - F1-score  
   - Confusion Matrix  
5. **Feature Importance Visualization:**  
   - Identify key factors influencing churn.

---

## 🧑‍💻 Tech Stack
- Python 3.x  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib, Seaborn  
- Jupyter Notebook

---

## 📊 Results

Three models were trained to predict customer churn:

| Model                | Accuracy | F1-Score |
|----------------------|----------|----------|
| Logistic Regression  | ~80%     | ~0.62    |
| Random Forest        | ~85%     | ~0.67    |
| XGBoost              | ~86%     | ~0.68    |

✅ **Best Model:** XGBoost (highest accuracy and F1-score).

**Sample Visualization:**  
*(Add sample images or graphs from your results folder, e.g., feature importance plot)*  
![Feature Importance](images/feature_importance.png)

---

## 🚀 Installation & Usage

### 1. Clone the repository
```bash
git clone https://github.com/ahmedengineer-seecs/customer-churn-prediction.git
cd customer-churn-prediction
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Jupyter Notebook
```bash
jupyter notebook notebooks/churn_prediction.ipynb
---

## 🤝 Contributing

Contributions are welcome!  
If you'd like to improve the models, clean the code, or add new features, please fork the repo and submit a pull request.

---

## 📬 Contact

For questions, suggestions, or collaboration, reach out to [ahmedmagsiaa085@gmail.com] or open an issue in this repository.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

