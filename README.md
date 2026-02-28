# House Price Prediction using Machine Learning

This project analyzes housing data from King County, USA and builds regression models to predict house prices based on property features.

---

## Project Overview

The objective of this project is to understand how different house attributes influence sale prices and to develop machine learning models that can accurately predict house prices.

The workflow includes data cleaning, exploratory data analysis (EDA), feature correlation analysis, model building, and performance evaluation.

---

## Dataset

The dataset used in this project is the King County housing dataset, which contains information about house sales in King County, USA.

It includes features such as:
- Bedrooms  
- Bathrooms  
- Living area (sqft_living)  
- Waterfront  
- Grade  
- Latitude and Longitude  
- Basement area  
- Year built  
- And other structural attributes  

---

## Project Workflow

### 1. Data Loading and Cleaning
- Loaded the dataset using Pandas  
- Checked data types and summary statistics  
- Handled missing values in key columns  

### 2. Exploratory Data Analysis
- Visualized feature distributions  
- Plotted relationships between important variables  
- Analyzed the distribution of house prices  

### 3. Feature Correlation Analysis
- Examined correlations between house features and price  
- Identified influential variables such as living area and grade  

### 4. Model Building
- Implemented Linear Regression  
- Applied Ridge Regression for regularization  
- Used Polynomial Features to capture non-linear relationships  
- Built pipelines for structured and clean model training  

### 5. Model Evaluation
- Performed train-test split  
- Evaluated models using R² score  
- Compared performance across different models  

---

## Key Observations

- Houses with larger living areas tend to have higher prices.  
- Waterfront properties are generally more expensive.  
- Features such as grade and location strongly influence house prices.  
- Polynomial features slightly improved prediction accuracy.  
- Ridge Regression helped reduce overfitting.  

---

## Models Used

- Linear Regression  
- Ridge Regression  
- Polynomial Ridge Regression  

---

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## Conclusion

This project demonstrates a complete regression workflow including data preprocessing, exploratory analysis, model development, regularization, and evaluation. It highlights how feature engineering and regularization techniques improve predictive performance in real-world datasets.
