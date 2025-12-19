# 📊 Customer Churn Prediction

This project focuses on predicting customer churn using the **Telco Customer Churn Dataset**. The goal is to identify key factors that lead to customer attrition and to build predictive models that can help telecom companies improve customer retention strategies.

---

## 🧠 Project Overview

Customer churn occurs when customers discontinue their service with a company. By analyzing patterns in customer demographics, account details, and service usage, this project aims to:
- Understand the drivers behind customer churn.
- Perform exploratory data analysis (EDA) and visualize key insights.
- Build and evaluate machine learning models to predict churn likelihood.

---

## 📁 Dataset

**Dataset Used:** `Telco-Customer-Churn.csv`

**Description:**  
The dataset contains customer data from a telecom company, including demographic information, account details, and services used.

**Key Features:**
- `customerID` – Unique customer identifier  
- `gender`, `SeniorCitizen`, `Partner`, `Dependents` – Demographics  
- `tenure`, `Contract`, `PaymentMethod`, `MonthlyCharges`, `TotalCharges` – Customer account information  
- `InternetService`, `TechSupport`, `StreamingTV`, `StreamingMovies`, etc. – Services subscribed  
- `Churn` – Target variable indicating if the customer has churned (`Yes` or `No`)

---

## 🧹 Data Preprocessing

Steps performed:
1. Imported and inspected the dataset.
2. Handled missing values and data type conversions.
3. Encoded categorical variables into numeric format.
4. Scaled numerical features using **StandardScaler**.
5. Split the dataset into **training** and **testing** sets for model building.

---

## 📊 Exploratory Data Analysis (EDA)

Key analyses performed using **Seaborn** and **Matplotlib**:
- Distribution of churned vs. retained customers.
- Relationship between churn and:
  - Contract type
  - Payment method
  - Tenure length
  - Internet services
- Correlation heatmaps to identify significant numerical relationships.

---

## 🤖 Machine Learning Models

Implemented models:
- **Logistic Regression**
- **Decision Tree Classifier**

**Model Evaluation Metrics:**
- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

---

## 🧪 Results Summary

| Model | Accuracy | Highlights |
|--------|-----------|------------|
| Logistic Regression | ~80–83% | Performs well on standardized numerical data. |
| Decision Tree Classifier | ~85–88% | Captures non-linear relationships but prone to overfitting. |

*(You can replace the accuracy values with your actual results.)*

---

## 🚀 How to Run the Project

### Prerequisites
Install the required dependencies:
```bash
pip install pandas numpy seaborn matplotlib scikit-learn

Steps to Execute
1. Open the Jupyter Notebook:
jupyter notebook "Customer Churn.ipynb"
2. Execute all cells

---

## 🧰 Technologies Used

Python
Pandas, NumPy – Data manipulation
Seaborn, Matplotlib – Data visualization
Scikit-learn – Machine learning and evaluation

---

###🔮 Future Improvements

- Implement Random Forest and XGBoost models for better performance.
- Use GridSearchCV for hyperparameter optimization.
- Deploy the trained model using Flask or Streamlit.
- Automate EDA reporting.
