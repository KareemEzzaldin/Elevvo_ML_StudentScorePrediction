# Student Score Prediction

Predict student exam scores using machine learning.

---

## Overview

This project builds a regression model to estimate student exam scores based on study hours and related factors.  
The notebook performs data cleaning, visualization, encoding, and model evaluation.  
Both **Linear Regression** and **Polynomial Regression** models are tested and compared.

---

## Steps

- Load and inspect dataset  
- Handle missing and duplicate data  
- Visualize numerical and categorical features  
- Encode categorical data with LabelEncoder  
- Split data into train and test sets  
- Train Linear Regression and Polynomial Regression models  
- Compare model performance using MAE, MSE, and R²  
- Visualize actual vs predicted scores  

---

## Dataset

**File:** `StudentPerformanceFactors.csv`  
Contains attributes like:

- `Hours_Studied`  
- `Teacher_Quality`  
- `Parental_Education_Level`  
- `Gender`  
- `Distance_from_Home`  
- `Exam_Score`

Target variable: **Exam_Score**

---

## Requirements

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
