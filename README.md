# 📊 Customer Churn Prediction

A machine learning project that predicts whether a telecom customer is likely to churn based on customer demographics, services, contract details, tenure, and billing information.

## 🎯 Project Objective

Customer churn is an important problem for subscription-based businesses.

The goal of this project is to use historical customer data to identify customers who are likely to leave the service.

The project includes:

* Data cleaning
* Exploratory Data Analysis (EDA)
* Feature preprocessing
* Categorical encoding
* Numerical feature scaling
* Machine Learning classification
* Model evaluation
* Streamlit web application

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib
* Streamlit

## 🤖 Machine Learning

The project uses Logistic Regression for binary classification.

The target variable is:

* `0` → Customer will stay
* `1` → Customer may churn

### Preprocessing

Numerical features are scaled using StandardScaler.

Categorical features are converted into numerical form using One-Hot Encoding.

The preprocessing and machine learning model are combined using a Scikit-learn Pipeline.

## 📊 Dataset

The dataset contains customer information related to:

* Demographics
* Customer tenure
* Phone services
* Internet services
* Online security
* Technical support
* Streaming services
* Contract type
* Payment method
* Monthly charges
* Total charges

The target variable is `Churn`.

## 🌐 Streamlit Application

The project includes an interactive Streamlit interface where users can enter customer information and receive a churn prediction.

### Application Screenshot

![Streamlit Application](screenshots/streamlit_home.png)

### Prediction Result

![Prediction Result](screenshots/prediction_result.png)

## 🔄 Project Workflow

```text
Customer Dataset
       ↓
Data Cleaning
       ↓
Exploratory Data Analysis
       ↓
Feature Selection
       ↓
Train-Test Split
       ↓
Data Preprocessing
       ↓
Logistic Regression
       ↓
Model Evaluation
       ↓
Streamlit Application
       ↓
Customer Churn Prediction
```

## 💡 Business Use

The prediction can help businesses identify customers who may be at risk of leaving.

This can support actions such as:

* Customer retention campaigns
* Personalized offers
* Customer support follow-ups
* Service improvement

## 📌 Project Type

Machine Learning | Classification | Data Science | Streamlit
