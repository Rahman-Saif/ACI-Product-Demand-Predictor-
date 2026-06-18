# 📈 ACI Product Demand Predictor

## Overview

The **ACI Product Demand Predictor** is a machine learning-based demand forecasting system developed to predict future product demand using historical sales-related features. Accurate demand prediction helps businesses optimize inventory management, reduce stock shortages, and improve supply chain efficiency.

This project follows a complete machine learning workflow, including dataset generation, exploratory data analysis, feature engineering, model training, and performance evaluation.

Project Demo : 

<img width="1920" height="912" alt="image" src="https://github.com/user-attachments/assets/4deb5c30-3e73-448d-ab1f-5a0ba11dad8c" />


---

## 🎯 Objectives

- Forecast product demand using machine learning.
- Analyze factors influencing product sales.
- Compare multiple regression algorithms.
- Identify the best-performing model for demand prediction.

---

## 📊 Dataset

Since real-world business data is often confidential, a **synthetic dataset** was generated to simulate realistic product demand scenarios.

The dataset contains features related to:

- sale_id
- product_id
- product_name
- region
- season
- quantity
- sold
- sold_quantity
- sold_date	price
- cost
- profit
- revenue
- stock_required
- channel
- date

---

## 🔍 Exploratory Data Analysis (EDA)

Several analytical techniques were performed to understand the dataset:

- MOST & LEAST SOLD
- WEEKLY SALES TREND
- STOCK OUT PRODUCTS
- TOP RISK PRODUCTS
- WAREHOUSE WISE STOCK
- SEASON WISE TOP SOLD
- REGION WISE TOP SOLD
- PRODUCT GROWTH/DECLINE
- TOP REGIONS OF SALES
- TOP SELLS PER DISEASE

<img width="790" height="390" alt="image" src="https://github.com/user-attachments/assets/bfc32e5d-bb1e-4ab2-a7f7-9c42b43025a4" />
<img width="790" height="390" alt="image" src="https://github.com/user-attachments/assets/90f3d987-36af-40f5-9bad-ec2f3bb8a446" />
<img width="1790" height="1189" alt="image" src="https://github.com/user-attachments/assets/c818f04b-c86a-43bd-aa22-805066d25a6b" />
<img width="1384" height="790" alt="image" src="https://github.com/user-attachments/assets/1f49d07d-5010-4c9a-94f7-2a8c166f41a2" />
<img width="1189" height="790" alt="image" src="https://github.com/user-attachments/assets/a59f28ef-d5be-4746-9164-96292cb4f0e0" />
etc 
---

## ⚙️ Data Preprocessing

The following preprocessing steps were applied:

- Data cleaning
- Handling missing values
- Feature selection
- Feature encoding
- Feature scaling
- Train-test splitting

---

## 🤖 Machine Learning Models

The following regression algorithms were trained and evaluated:

1. LightGBM Regressor
2. Linear Regression
3. XGBoost Regressor
4. Gradient Boosting Regressor
5. Random Forest Regressor
6. Decision Tree Regressor

---

## 📈 Model Performance

| Model | MAE | RMSE |
|---------|---------|---------|
| LightGBM | 3.538 | 4.228 |
| Linear Regression | 3.541 | 4.229 |
| XGBoost | 3.558 | 4.269 |
| Gradient Boosting | 3.562 | 4.275 |
| Random Forest | 3.616 | 4.406 |
| Decision Tree | 4.708 | 5.980 |

### 🏆 Best Model: LightGBM

- **MAE:** 3.538
- **RMSE:** 4.228

LightGBM achieved the lowest prediction error among all evaluated models, making it the most effective model for demand forecasting in this project.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- LightGBM
- Jupyter Notebook

---

## 🚀 Project Workflow

```text
Synthetic Dataset Generation
           ↓
Data Exploration & Analysis
           ↓
Data Preprocessing
           ↓
Feature Engineering
           ↓
Model Training
           ↓
Performance Evaluation
           ↓
Best Model Selection
```

---

## 📌 Key Insights

- Ensemble boosting models achieved the best forecasting performance.
- LightGBM and Linear Regression produced nearly identical results.
- Decision Tree showed the highest prediction error among all models.
- Machine learning can effectively forecast product demand and support inventory planning decisions.

---

## 🔮 Future Improvements

- Integrate real-world retail sales data.
- Apply advanced time-series forecasting techniques.
- Deploy the model using Flask, FastAPI, or Streamlit.
- Develop an interactive dashboard for business users.
- Incorporate inventory optimization recommendations.

---



## 👨‍💻 Author

**Rahman Saif**

Machine Learning | Data Science | Artificial Intelligence | Predictive Analytics
