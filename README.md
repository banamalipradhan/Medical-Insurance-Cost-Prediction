# Medical Insurance Cost Prediction using Machine Learning

This project aims to build a regression model that can estimate a person’s medical insurance cost based on their demographic and lifestyle details.


## Problem Statement

Insurance companies face challenges in estimating correct premium values. Overpricing leads to customer dissatisfaction, while underpricing causes financial loss.  
This project focuses on predicting insurance charges using machine learning to support better decision-making and pricing strategies.

---

## Objective

- Analyze key factors influencing medical insurance charges  
- Build a prediction model using regression techniques  
- Measure performance of the model using standard evaluation metrics  
- Interpret insights to understand important cost-driving features  

---

## Dataset Overview

The dataset contains **1,338 records** with **7 features** including:  
:contentReference[oaicite:0]{index=0}

- age – age of the individual  
- sex – gender  
- bmi – body mass index  
- children – number of dependents  
- smoker – smoking habit  
- region – residential location  
- charges – target variable (insurance cost)

All columns have **0 missing values**, ensuring a clean dataset.  
:contentReference[oaicite:1]{index=1}

---

## Workflow

1. **Loading and Inspecting Dataset**  
   Dataset structure and data types reviewed  
   :contentReference[oaicite:2]{index=2}  

2. **Exploratory Data Analysis**  
   - Statistical summary for numerical features  
   - Distribution analysis (e.g., BMI distribution)  
   :contentReference[oaicite:3]{index=3}  

3. **Data Preprocessing**  
   - Encoded categorical features: sex, smoker, region  
   :contentReference[oaicite:4]{index=4}  

4. **Feature and Target Splitting**  
   Model trained on independent variables to predict insurance charges  

5. **Model Training**  
   A regression model was trained using the processed dataset  
   (shown in your notebook workflow)

6. **Model Evaluation**  
   Evaluation done on test set using:
   - R² Score  
   - Mean Absolute Error (MAE)  
   - Mean Squared Error (MSE)  
   :contentReference[oaicite:5]{index=5}  

---

## Results & Performance

Performance Metrics from the trained model:  
:contentReference[oaicite:6]{index=6}

- R² Score: **0.7447**  
- MAE: **4267.21**  
- MSE: **38337035.48**

These scores show that the model explains around **74%** of the variation in insurance charges, which is a strong baseline for a simple regression model.

---

## Key Insights

- Smoking status has the strongest impact on insurance charges  
- Higher BMI tends to increase medical cost due to health-related risks  
- Age also positively correlates with cost  
- Gender and region show limited impact compared to medical/lifestyle factors

---

## Technologies Used

- Python  
- NumPy, Pandas  
- Seaborn, Matplotlib  
- Scikit-Learn  
- Jupyter Notebook  
- Pickle (for model saving)


