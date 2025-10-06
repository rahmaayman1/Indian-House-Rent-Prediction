# Indian House Rent Prediction

## Project Overview
This project is a **Machine Learning model** designed to predict house rent prices in India based on various property features such as city, number of bedrooms, size, furnishing status, and more.

The goal is to build an accurate regression model that can estimate rent prices and help both tenants and property owners make data-driven decisions.

---

## Project Steps

### 1. Data Cleaning & Preprocessing
- Handled missing values and duplicates  
- Removed unnecessary or repeated columns  
- Detected and removed outliers  
- Encoded categorical variables  
- Scaled numerical features for better model performance  

### 2. Exploratory Data Analysis (EDA)
- Visualized correlations and distributions  
- Analyzed city-wise and BHK-wise rent variations  
- Identified key factors affecting rent prices  

### 3. Feature Engineering
- Created new derived features  
- Encoded text columns  
- Reduced noise and improved model interpretability  

### 4. Model Building
Trained and compared multiple regression models:
- Linear Regression  
- Ridge Regression  
- Lasso Regression  
- Decision Tree  
- Random Forest  
- XGBoost  
- LightGBM  

Evaluation metrics used:
- **R² Score**
- **MAE (Mean Absolute Error)**
- **RMSE (Root Mean Squared Error)**

### 5. Hyperparameter Tuning
- Used **GridSearchCV** for fine-tuning the best model (**XGBoost**)  
- Achieved improved accuracy and generalization  

---

## 📊 Model Performance

| Model | R² Score | MAE | RMSE |
|-------|-----------|-----|------|
| XGBoost | 0.9499 | 0.03 | 0.27 |
| Random Forest | 0.8940 | 0.03 | 0.39 |
| Linear Regression | 0.6749 | 0.24 | 0.68 |
| Ridge Regression | 0.6748 | 0.24 | 0.68 |
| Lasso Regression | 0.0054 | 0.51 | 1.19 |

 **Best Model:** XGBoost  
 **After Hyperparameter Tuning:**  
- R² Score: **0.9145**  
- MAE: **0.04**  
- RMSE: **0.35**

---

## Tech Stack
- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn**
- **XGBoost, LightGBM**
- **Jupyter Notebook**

---

## How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/rahmaayman1/Indian-House-Rent-Prediction.git
