🏠 House Price Prediction using Linear Regression
📌 Project Overview

This project focuses on predicting house prices using the Linear Regression machine learning algorithm. The model is trained on a housing dataset containing various features such as area, location type, number of rooms, etc., to estimate the house price accurately.

The project is implemented using Python in Jupyter (Jupyter Lite / Pyodide) and demonstrates the complete machine learning workflow including data preprocessing, model training, evaluation, and visualization.

🎯 Objectives

Understand the working of Linear Regression

Perform data cleaning and preprocessing

Handle categorical variables using encoding techniques

Train and evaluate a regression model

Visualize predicted vs actual house prices

📂 Dataset

File Name: housing_price_dataset.csv

Description: Contains numerical and categorical features related to houses along with the target variable Price.

🛠️ Technologies Used

Python

Jupyter Notebook (Jupyter Lite)

Pandas

NumPy

Matplotlib

Scikit-Learn

Note: Seaborn is not used as it is not supported in Jupyter Lite.

🔄 Project Workflow
1. Data Loading

Load CSV dataset using Pandas

2. Data Exploration

View dataset structure

Check data types and missing values

3. Data Preprocessing

Handle missing values

Convert categorical columns (e.g., Rural, Urban) using One-Hot Encoding

Ensure all features are numerical

4. Feature Selection

Independent variables → X

Target variable → Price

5. Train-Test Split

80% training data

20% testing data

6. Model Training

Linear Regression model trained using Scikit-Learn

7. Model Evaluation

Mean Squared Error (MSE)

R² Score

8. Visualization

Scatter plot of actual vs predicted house prices using Matplotlib

📊 Evaluation Metrics

Mean Squared Error (MSE): Measures average squared difference between actual and predicted prices

R² Score: Indicates how well the model explains price variations

🧠 Key Learnings

Importance of data preprocessing

Handling categorical data in regression models

Interpreting regression coefficients

Understanding model accuracy using evaluation metrics

⚠️ Known Issues & Solutions

Issue:

ValueError: could not convert string to float


Solution:
Applied One-Hot Encoding using:

pd.get_dummies(df, drop_first=True)

🚀 Future Enhancements

Add feature scaling

Try Polynomial Regression

Use advanced regression models

Deploy model using a web interface
