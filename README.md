## PREDICTIVE ANALYSIS USING MACHINE LEARNING

COMPANY: CODTECH IT SOLUTIONS

NAME: SRIPADA ARUN

INTERN ID: CT08DF2529

DOMAIN: Data Analytics

MENTOR: NEELA SANTOSH

# Netflix Global Revenue Prediction using Machine Learning

This project uses historical Netflix streaming data to **predict global revenue** using regression models. It demonstrates data cleaning, feature engineering, model building, and evaluation — all inside a Jupyter Notebook.


## Files Included

- `Netflix_Revenue.ipynb` — Main notebook with all code
- `netflix_revenue_updated.csv` — Dataset used for training and evaluation


## Problem Statement

The goal is to predict **Global Revenue** based on regional revenues, member counts, ARPU, and other metrics using:
- Linear Regression
- Random Forest Regression


## Key Features

- Clean and preprocess the Netflix revenue dataset
- Visualize correlation using **heatmaps**
- Select features based on correlation and domain knowledge
- Train and compare multiple regression models
- Evaluate using **R², RMSE, MAE**
- Visualize model results and feature importance with **bar charts**


## Technologies Used

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- Jupyter Notebook


## Evaluation Results

| Model              | R² Score | RMSE         | MAE          |
---------------------------------------------------------------
| Linear Regression  | 0.997    | ₹87 Million  | ₹86 Million  |
| Random Forest      | 0.915    | ₹443 Million | ₹311 Million |


## How to Run the Project

1. Download the CSV files
2. Using VS Code or Jupyter load the data
3. Clean Colunm names and convert the data to datetime sort
4. Target the Feature selection and Split the data
5. Use Train models and Predictions
6. evaluation metrics and Feature importance from Random Forest
7. Save as 'file name.ipynb'
8. Open the `.ipynb` notebook using Jupyter or VS Code
9. Run the cells step-by-step

Make sure your dataset (`netflix_revenue_updated.csv`) is in the same folder.

## Author

-  **[Sripada.Arun]**
-  [sripadaarun16@gmail.com]
