# Student Performance Analysis & Prediction

This project analyzes student exam performance and predicts math scores using machine learning techniques.

## Problem Statement
Understand which factors influence student performance and build a model to predict math scores.

## Dataset
Students Performance in Exams dataset from Kaggle.

## Tools & Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Approach
1. Data cleaning and inspection  
2. Exploratory Data Analysis (EDA)  
3. Feature encoding  
4. Model training using Linear Regression  
5. Model evaluation using R² and RMSE  

## Results
The model achieved an R² score of ~0.88 with an RMSE of ~5.4.

## How to Run
1. Install dependencies:
   ```
   pip install pandas matplotlib seaborn scikit-learn
   ```
2. Run Jupyter Notebook:
   ```
   jupyter notebook
   ```
3. Open `student_performance.ipynb`

## Project Structure
```
student-performance-analysis/
│── data/
│   └── StudentsPerformance.csv
│── student_performance.ipynb
│── README.md
```