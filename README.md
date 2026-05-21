
# Prediction of Customer Churn for Naijaconnect Company

## Project Overview
This project predicts customer churn for Naijaconnect using supervised machine learning models. The aim is to identify customers likely to leave the telecom service and support targeted retention strategies.

---

## Business Problem
Customer churn is a major issue in the Nigerian telecom industry due to high competition and customer acquisition costs. Naijaconnect seeks to identify high-risk customers early using customer demographics, usage behaviour, payment history, and service quality data.

---

## Machine Learning Workflow

### 1. Data Preprocessing
- Missing value checks
- Dropping irrelevant columns
- Data visualization
- Feature engineering

### 2. Feature Engineering
Derived features include:

| Feature | Description |
|---|---|
| customer_value_score | Customer monetary value |
| service_experience_score | Service quality indicator |
| competitors_risk_level | Competitor switching risk |
| usage_efficiency_level | Usage-to-cost efficiency |
| digital_engagment_level | Digital platform engagement |
| high_value_customer_satistfaction | High-value customer satisfaction tracking |

---

## Encoding Techniques
- Label Encoding
- Frequency Encoding
- One-Hot Encoding
- Ordinal Encoding

---

## Feature Reduction & Selection
- Variance Threshold
- SelectKBest (ANOVA F-test)

---

## Models Used
- Logistic Regression
- Random Forest
- Gradient Boosting

---

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Cross Validation Accuracy

---

## Hyperparameter Tuning
GridSearchCV was used for model optimization.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---




---

