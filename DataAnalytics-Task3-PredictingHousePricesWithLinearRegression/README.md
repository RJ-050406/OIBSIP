# Task 3 – Predicting House Prices with Linear Regression

## Objective
The objective of this project is to build a Machine Learning model to predict house prices based on various property features using the Ames Housing dataset.

## Dataset
**Ames Housing Dataset**

- Rows: 2,930
- Columns: 82
- Target Variable: `SalePrice`

## Steps Performed
1. **Data Loading & Exploration**
   - Loaded the Ames Housing dataset.
   - Checked the dataset structure, data types, and statistical summary.

2. **Exploratory Data Analysis**
   - Analyzed the distribution of `SalePrice`.
   - Studied correlations between numerical features and house prices.
   - Created a correlation heatmap.

3. **Data Preprocessing**
   - Handled missing values based on the meaning of each feature.
   - Separated features (`X`) and target variable (`y`).
   - Removed identifier columns that were not useful for prediction.
   - Applied One-Hot Encoding to categorical features.

4. **Feature Preparation**
   - Identified numerical and categorical features.
   - Created the final feature matrix with 318 features.

5. **Model Training**
   - Split the data into training and testing sets using an 80/20 split.
   - Trained a Linear Regression model.
   - Trained a Ridge Regression model for comparison.

6. **Model Evaluation**
   - Evaluated the models using MSE, RMSE, and R² Score.
   - Created Actual vs Predicted and Residual plots.
   - Performed coefficient analysis for the Linear Regression model.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Outcome
- Successfully analyzed the **Ames Housing dataset** containing 2,930 records and 82 features.
- Performed EDA to understand the **distribution of house prices and relationships between features**.
- Handled missing values appropriately and achieved a **complete dataset with no remaining null values**.
- Applied **One-Hot Encoding** to categorical features, resulting in a final feature matrix of **318 features**.
- Trained a **Linear Regression model** using an 80/20 train-test split.
- Linear Regression achieved an **R² Score of 0.8946** and an **RMSE of 29,063.28**.
- Compared Linear Regression with **Ridge Regression**, and Linear Regression performed slightly better on the test data.
- Used **coefficient analysis, Actual vs Predicted plots, and Residual plots** to understand model performance and feature effects.
