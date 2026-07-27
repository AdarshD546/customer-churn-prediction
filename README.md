# 📊 Customer Churn Prediction

A Machine Learning project that predicts whether a customer is likely to leave (churn) based on their banking information. This project uses classification algorithms to help businesses identify at-risk customers and improve customer retention strategies.

---

## 📌 Project Overview

Customer churn is one of the biggest challenges for businesses. Losing existing customers can be more expensive than acquiring new ones. This project builds a predictive model using customer demographic and financial data to determine whether a customer will exit the bank.

---

## 📂 Dataset

**Dataset:** `Churn_Modelling.csv`

The dataset contains **10,000 customer records** with **14 features**.

### Features

| Feature | Description |
|---------|-------------|
| RowNumber | Record ID |
| CustomerId | Unique customer ID |
| Surname | Customer surname |
| CreditScore | Customer credit score |
| Geography | Customer's country |
| Gender | Male/Female |
| Age | Customer age |
| Tenure | Years with the bank |
| Balance | Account balance |
| NumOfProducts | Number of bank products |
| HasCrCard | Has credit card (0/1) |
| IsActiveMember | Active member (0/1) |
| EstimatedSalary | Estimated salary |
| Exited | Target variable (1 = Churn, 0 = No Churn) |

---

## 🎯 Objective

Build a machine learning model that predicts whether a customer will leave the bank based on historical customer data.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📈 Project Workflow

1. Import Dataset
2. Data Exploration
3. Data Cleaning
4. Feature Encoding
5. Feature Scaling
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Prediction

---

## 🤖 Machine Learning Models

You can train and compare multiple classification algorithms such as:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- XGBoost *(optional)*

---

## 📊 Evaluation Metrics

The model performance can be evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC-AUC Score

---

## 📁 Project Structure

```
Customer-Churn-Prediction/
│
├── Churn_Modelling.csv
├── customer_churn.ipynb
├── requirements.txt
├── README.md
└── models/
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/your-username/customer-churn-prediction.git
```

Go to the project folder

```bash
cd customer-churn-prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook

```bash
jupyter notebook
```

---

## 📦 Requirements

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

---

## 📌 Sample Output

The model predicts:

- **0** → Customer will stay
- **1** → Customer is likely to leave

Example:

```
Prediction: 1
Customer is likely to churn.
```

---

## 📉 Business Benefits

- Identify customers likely to leave
- Improve customer retention
- Reduce revenue loss
- Design targeted marketing campaigns
- Increase customer satisfaction

---

## 🔮 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Deploy using Flask or Streamlit
- Real-time prediction API
- Interactive dashboard

---

## 👨‍💻 Author

**Adarsh Deore**

Artificial Intelligence & Data Science Student

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
