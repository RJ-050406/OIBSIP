# Task 4 – Wine Quality Prediction

## Objective
The objective of this project is to predict wine quality based on its physicochemical properties using machine learning classification models. The original quality scores were converted into two categories, **Bad** and **Good**, to make the classification problem more practical.

## Dataset Details
The Wine Quality – Red dataset contains **1,599 rows and 12 columns**, including 11 physicochemical features and the target variable `quality`.  

## Steps Performed
### 1. Data Loading and Inspection
Loaded the Wine Quality dataset and examined its structure, dimensions, data types, and statistical summary.

### 2. Data Cleaning
Checked for missing values and duplicate records. No missing values were found, while duplicate records were removed.

### 3. Exploratory Data Analysis
Used histograms to analyze feature distributions and a correlation heatmap to understand relationships between the chemical properties.

### 4. Class Distribution Analysis
Analyzed the distribution of wine quality scores and identified that scores 5 and 6 were the most common, while scores 3 and 8 were less represented.

### 5. Feature Engineering
Converted the original quality scores into two classes:
- **Bad:** 3–5
- **Good:** 6–8

### 6. Train-Test Split
Separated the input features and target variable and divided the dataset into **80% training and 20% testing data** using stratified sampling.

### 7. Model Training
Trained three classification models:
- Random Forest Classifier
- SGD Classifier
- Support Vector Classifier (SVC)

### 8. Model Evaluation
Evaluated the models using accuracy, precision, recall, F1-score, classification reports, and confusion matrices.

### 9. Feature Importance Analysis
Used Random Forest to identify and visualize the most important features for predicting wine quality.

### 10. Model Comparison
Compared the performance of all three models and selected the model with the best overall performance.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Outcome
- Successfully developed a machine learning classification system for predicting wine quality as **Bad** or **Good**.
- After removing duplicate records, **1,359 observations** were used for analysis.
- Quality scores **5 and 6** were the most frequently occurring classes in the dataset.
- The original quality scores were converted into **Bad (3–5)** and **Good (6–8)** categories.
- **Random Forest** achieved an accuracy of **75.00%**.
- **SGD Classifier** achieved an accuracy of **72.43%**.
- **SVC achieved the highest accuracy of 75.37%** among the three models.
- SVC also achieved the best overall **F1-score performance** for both Bad and Good classes.
- Random Forest feature importance showed that **alcohol** was the most influential feature, followed by **sulphates** and **volatile acidity**.
- Based on the overall evaluation, **SVC was selected as the most suitable model** for this wine quality classification task.
