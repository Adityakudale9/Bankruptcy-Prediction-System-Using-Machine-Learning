**** Bankruptcy Prediction System Using Machine Learning ****

## Project Overview
In today’s financial environment, predicting whether a company may go bankrupt is extremely important for investors, banks, and stakeholders. This project focuses on building a machine learning system that can analyze financial data and predict the likelihood of bankruptcy at an early stage.

The goal of this project is to reduce financial risk by identifying warning signs in company data before failure occurs. Instead of relying on manual financial analysis, this system uses data-driven techniques to make faster and more accurate predictions.

----------------------------------------------------------------------------------

## Problem Statement
Many companies fail due to poor financial health, but traditional analysis methods are:
- Time-consuming  
- Error-prone  
- Limited in handling complex data  

This project solves these problems by applying machine learning models to detect patterns that indicate financial instability.

---

## Approach & Methodology

The project follows a structured data science pipeline:

### 1. Data Preprocessing
- Handled missing values  
- Removed outliers using IQR method  
- Normalized and cleaned financial data  

### 2. Feature Selection
- Used SelectKBest (Chi-Square)  
- Selected most important financial indicators  
- Reduced noise and improved model performance  

### 3. Model Building
Implemented and compared multiple machine learning models:
- Logistic Regression  
- Decision Tree  
- Random Forest  
- K-Nearest Neighbors  

### 4. Model Evaluation
- Accuracy Score  
- Confusion Matrix  
- Classification Report (Precision, Recall, F1-score)  

------------------------------------------------------------

## Key Results

- Random Forest achieved the highest accuracy (~91%)  
- Feature selection significantly improved performance  
- Ensemble methods performed better on complex financial data  

The model can effectively distinguish between:
- Bankrupt companies  
- Financially stable companies  

--------------------------------------------------------------------

## Visual Analysis

The project includes multiple visualizations to understand data patterns:

- Industrial Risk Distribution  
- Correlation Heatmap  
- Outlier Detection (Z-score)  
- Operating Risk Distribution  

-----------------------------------------------------------

## Streamlit Application

An interactive web application was developed using Streamlit where users can:

- Input financial parameters  
- Get real-time prediction  
- View probability of bankruptcy  

This makes the system practical and user-friendly.

---------------------------------------------------------------------

## Technologies Used

- Python  
- Pandas and NumPy  
- Matplotlib and Seaborn  
- Scikit-learn  
- Streamlit  



