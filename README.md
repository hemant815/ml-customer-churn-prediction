# 📊 Customer Churn Prediction

Predict customer churn using Machine Learning by analyzing customer demographics, account information, and service usage patterns.

---

## 🚀 Project Overview

Customer churn is one of the biggest challenges faced by telecom companies. This project aims to predict whether a customer is likely to leave the company based on various customer attributes.

The project covers the complete Machine Learning workflow, including:

* Data Cleaning and Preprocessing
* Feature Engineering
* Handling Imbalanced Data
* Feature Scaling and PCA
* Training Multiple Classification Models
* Hyperparameter Tuning with GridSearchCV
* Model Evaluation and Comparison

---

## 📁 Dataset

* **Dataset:** Telco Customer Churn Dataset
* **Rows:** 7043
* **Features:** 20+
* **Target Variable:** `Churn`

### Target Classes

* **0 → No Churn**
* **1 → Churn**

---

## ⚙️ Project Workflow

### 1. Data Cleaning

* Removed unnecessary columns
* Converted data types
* Handled missing values and duplicates

### 2. Feature Engineering

* Binary encoding
* One-Hot Encoding
* Standardization using StandardScaler
* Principal Component Analysis (PCA)

### 3. Train-Test Split

* Stratified sampling
* Preserved class distribution

### 4. Handling Imbalanced Data

* Used `class_weight='balanced'`

### 5. Model Training

Implemented and compared multiple classification algorithms:

* Logistic Regression
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* Naive Bayes
* XGBoost

### 6. Hyperparameter Tuning

Applied GridSearchCV to optimize model performance.

### 7. Evaluation Metrics

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score

---

## 🛠 Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost

---

## 📈 Machine Learning Models

| Model               |
| ------------------- |
| Logistic Regression |
| Decision Tree       |
| Random Forest       |
| SVM                 |
| KNN                 |
| Naive Bayes         |
| XGBoost             |

---

## 📊 Results

The performance of all models was compared using:

* Accuracy
* Precision
* Recall
* F1 Score

The best-performing model was selected based on overall classification performance.

---

## 📂 Repository Structure

```text
customer-churn-prediction/
│
├── Customer_Churn_Prediction.ipynb
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── README.md
├── requirements.txt
```

---

## 🔮 Future Improvements

* Feature Importance Analysis
* Model Deployment with Streamlit
* Pipeline Creation using Scikit-Learn
* Save and Load Model using Pickle

---

## 🎯 Key Skills Demonstrated

✔ Data Cleaning and Preprocessing

✔ Feature Engineering

✔ Exploratory Data Analysis

✔ Feature Scaling and PCA

✔ Handling Imbalanced Data

✔ Classification Algorithms

✔ Hyperparameter Tuning

✔ Model Evaluation and Comparison

---

## 🤝 Connect With Me

If you found this project useful, feel free to ⭐ the repository and connect with me on LinkedIn.

---

**Made with ❤️ using Python and Machine Learning**
