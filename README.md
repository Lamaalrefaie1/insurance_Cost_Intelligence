# Insurance Cost Intelligence

This project builds a machine learning model to predict insurance costs based on health and demographic variables.
The goal is to explore how data science can support operational decision making in healthcare insurance environments.

## Problem Statement
Insurance cost behavior is often analyzed after costs occur.
In this project, I built a predictive model to estimate insurance charges using structured member data.
The idea is to understand which factors influence cost and how predictive modeling can support smarter decision processes.

## Dataset
The dataset includes:
1. Age
2. Gender
3. BMI
4. Smoking Status
5. Diabetic Status
6. Region
7. Charges


## Project Steps: 
1. Data Exploration (EDA):
   - Checked data structure and distribution
   - Analyzed cost distribution
   - Reviewed correlations between variables
   - Identified important features
2. Data Preprocessing :
   - Converted categorical variables using Label Encoding
   - Applied StandardScaler for numerical features
   - Split data into training and testing sets
   - Saved preprocessing files:
     A. label_encoder_diabetic.pkl
     B. label_encoder_smoker.pkl
     C. label_encoder_diabetic.pkl
     D. scaler.pkl

## Model Training:

I tested multiple regression models:
  - Linear Regression
  - Polynomial Regression
  - Random Forest

Models were evaluated using:
  - R² Score
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)

Best Performing model was saved as **best_model.pkl**

## Key Findings:
- Smoking status has a strong impact on insurance charges
- BMI and age significantly influence predicted costs
- Random Forest performed better than basic linear models

## Why This Matters:
This type of model can help operations teams:
- Identify high risk members early
- Support cost forecasting
- Improve pricing strategy discussions
- Move from reactive analysis to predictive insights
