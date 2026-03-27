# Car-price-prediction
ML model to predict used car prices based on features like fuel type, transmission, and usage.
# 🚗 Car Price Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue)
![ML](https://img.shields.io/badge/Machine%20Learning-Linear%20Regression-green)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Library](https://img.shields.io/badge/Library-scikit--learn-orange)

---

## 📌 Project Overview
- This project predicts the **selling price of used cars**
- Built using **Machine Learning (Linear Regression)**
- Focuses on **data preprocessing, encoding, and model training**
- Handles real-world dataset issues like **categorical data & errors**

---

## 📂 Dataset Information
The dataset contains details of used cars with the following features:

- Car_Name  
- Year  
- Selling_Price  
- Present_Price  
- Kms_Driven  
- Fuel_Type  
- Selling_type  
- Transmission  
- Owner  

---

## ⚙️ Data Preprocessing
- Removed unnecessary column:
  - `Car_Name`
- Converted categorical values into numerical format using:
  - Label Encoding
- Cleaned column names to avoid `KeyError`
- Ensured dataset contains only numerical values

---

## 🤖 Model Used
- **Linear Regression** from `scikit-learn`

---

## 🔄 Workflow
1. Import libraries  
2. Load dataset  
3. Data preprocessing  
4. Encode categorical variables  
5. Train-test split  
6. Train model  
7. Prediction  
8. Evaluation  




