# Weight vs Height Prediction using Linear Regression

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
