# Customer Churn Prediction using Machine Learning

This project predicts whether a customer is likely to **churn (leave a company)** based on their demographic details, services, and billing information. It uses Python and Machine Learning models to analyze patterns and make predictions.

---

## Project Objective

The goal is to:
- Analyze customer behavior
- Build models to predict churn
- Help businesses retain customers by identifying at-risk users

---

## Tech Stack

- Python 🐍
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-Learn

---

## Dataset

File: `customer_churn.csv`

**Columns:**

- `customer_id` – Unique customer ID  
- `gender` – Male / Female  
- `senior_citizen` – 0 or 1  
- `partner` – Yes / No  
- `dependents` – Yes / No  
- `tenure` – Months with company  
- `phone_service` – Yes / No  
- `internet_service` – DSL / Fiber optic / No  
- `monthly_charges` – Monthly bill amount  
- `total_charges` – Total amount charged  
- `churn` – Yes / No (Target Variable)

---

## Workflow

1. Load the dataset
2. Clean missing values
3. Encode categorical features
4. Split into Train/Test sets
5. Train ML models:
   - Logistic Regression
   - Random Forest
6. Evaluate using:
   - Accuracy
   - Confusion Matrix
   - Classification Report

---

## Models Used

| Model               | Purpose                     |
|--------------------|-----------------------------|
| Logistic Regression | Baseline churn prediction   |
| Random Forest       | Improved accuracy & insights|

---

## Sample Results

- Accuracy Score
- Confusion Matrix
- Churn Distribution Plot

---

## How to Run

1. Clone the repo or download files  
2. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
