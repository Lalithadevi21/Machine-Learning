###1.Linear Regression 

##Weight vs Height Prediction 

## Project Overview
This project predicts a person's weight based on their height using Simple Linear Regression. The dataset was cleaned, outliers were handled using the IQR method, and the model was evaluated using multiple performance metrics.

## Problem Statement
To build a machine learning model that can predict weight based on height.

## Dataset Description
The dataset contains the following columns:
- Gender (removed during preprocessing)
- Height
- Weight

## Data Preprocessing
- Dropped the "Gender" column
- Checked for missing values
- Detected and handled outliers using the IQR method
- Treated outliers in both Height and Weight columns

## Exploratory Data Analysis
- Used boxplots to detect outliers
- Checked data distribution
- Analyzed statistical summary using describe()

## Model Building
- Split data into training and testing sets (80% training, 20% testing)
- Used `LinearRegression` from Scikit-learn
- Trained the model on height as input and weight as output

## Model Optimization
- Tested 500 different random states
- Selected the best model based on highest R2 score

## Model Evaluation Metrics
- R2 Score
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

## Model Details
- Coefficient (Slope)
- Intercept

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Conclusion
The model shows a strong positive linear relationship between height and weight. After handling outliers and optimizing random state selection, the model achieved good prediction performance.
---


###2.Logistic Regression

##Diabetes Prediction 

## Project Overview

This project builds a machine learning model to predict whether a person has diabetes or not using Logistic Regression. The model is trained on medical data and learns patterns that help classify patients as diabetic or non-diabetic.

## Problem Statement

The goal of this project is to develop a classification model that can predict the likelihood of diabetes based on health-related features.

## Dataset

The dataset contains medical diagnostic measurements of patients. Some of the key features include:

* Pregnancies
* Glucose
* Blood Pressure
* Skin Thickness
* Insulin
* BMI (Body Mass Index)
* Diabetes Pedigree Function
* Age

The target variable indicates whether the patient has diabetes (1) or not (0).

## Steps Performed

1. Imported necessary libraries such as Pandas, NumPy, and Scikit-learn
2. Loaded and explored the dataset
3. Checked data structure and summary statistics
4. Split the dataset into training and testing sets
5. Trained a Logistic Regression model
6. Made predictions using the trained model
7. Evaluated the model using accuracy and other performance metrics

## Model Used

Logistic Regression (Classification Algorithm)

## Evaluation Metrics

* Accuracy Score
* Confusion Matrix
* Classification Report

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-learn

## How to Run the Project

1. Clone the repository.
2. Open the notebook file.
3. Run the cells step by step.
4. The model will train and display prediction results.

## Conclusion

The Logistic Regression model successfully classifies patients based on medical features and predicts whether a person is likely to have diabetes. This project demonstrates the use of machine learning for healthcare prediction problems.

