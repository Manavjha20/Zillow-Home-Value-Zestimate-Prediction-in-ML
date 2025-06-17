# 🏡 Zillow Home Value Zestimate Prediction Using Machine Learning

This project develops a machine learning model to predict home values — similar to Zillow's "Zestimate." By leveraging real estate property data and applying advanced regression techniques, the model delivers accurate and reliable home price predictions.

---

## 📌 Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Methodology](#methodology)
  - [Data Cleaning](#data-cleaning)
  - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Data Preparation](#data-preparation)
  - [Model Selection and Training](#model-selection-and-training)
  - [Evaluation](#evaluation)
- [Results](#results)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [How to Run](#how-to-run)
- [License](#license)

---

## 🧠 Introduction

Real estate valuations are critical yet often subjective and time-consuming when done manually. This project automates the process using machine learning techniques, creating a Zillow-like home value estimator. It explores and compares several regression models to predict home prices accurately and efficiently.

---

## 📊 Dataset

The dataset includes various property features such as:

- Square footage  
- Number of bedrooms and bathrooms  
- Lot size  
- Year built  
- Location (e.g., zip code, neighborhood)  
- Property type  
- Tax information  

> *Note: The dataset is assumed to be pre-collected or sourced from a public real estate dataset.*

---

## 🛠️ Methodology

### ✅ Data Cleaning
- Imputed or removed missing values
- Treated outliers to reduce skew
- Removed highly correlated features to prevent multicollinearity

### 📈 Exploratory Data Analysis (EDA)
- Used visualizations to understand distributions and trends
- Identified key factors affecting home values

### 🧹 Data Preparation
- Feature engineering to enhance signal
- One-Hot Encoding for categorical variables
- Scaling of numerical features
- Removed irrelevant columns

### 🤖 Model Selection and Training
Regression models used:
- Linear Regression
- Ridge Regression (Best performing)
- Lasso Regression
- Random Forest Regressor
- XGBoost

**Target variable**: Logarithmic difference between actual and predicted home values.

### 📏 Evaluation
- **Metric**: Mean Absolute Error (MAE)  
- Lower MAE → Better model performance

---

## 📌 Results

Ridge Regression yielded the lowest MAE and provided the most stable predictions, showcasing its ability to manage multicollinearity and reduce overfitting.

---

## ✅ Conclusion

This project shows that machine learning can be a powerful tool in real estate valuation. Ridge Regression stood out as the best performer in our case, proving its effectiveness in handling real-world property data.

---

## 🚀 Future Work

- Add external data (e.g., crime rates, school scores, amenities)
- Use model explainability techniques like SHAP
- Deploy as a web app for real-time Zestimate predictions
- Experiment with deep learning models

---

## ▶️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/@Manavjha20/Zillow-Home-Value-Zestimate-Prediction.git
   cd Zillow-Home-Value-Zestimate-Prediction
