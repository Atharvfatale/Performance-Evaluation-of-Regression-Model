# Performance Evaluation of Regression Model

## Project Overview

This project implements and evaluates Regression Models for predicting Food Delivery Time using Machine Learning techniques. The objective is to analyze the performance of Standard Linear Regression and Linear Regression optimized using Gradient Descent.

The project includes data preprocessing, handling missing values, feature encoding, model training, prediction, performance evaluation, and convergence analysis of Gradient Descent.

---

## Dataset Information

* Dataset: Food Delivery Times Dataset
* Total Records: 1000
* Total Features: 9
* Target Variable: Delivery_Time_min

### Input Features

#### Numerical Features

* Distance_km
* Preparation_Time_min
* Courier_Experience_yrs

#### Categorical Features

* Weather
* Traffic_Level
* Time_of_Day
* Vehicle_Type

---

## Objectives

1. Develop a Regression Model for Food Delivery Time Prediction.
2. Evaluate model performance using R² Score, MAE, and RMSE.
3. Implement Gradient Descent from scratch.
4. Analyze convergence behavior of Gradient Descent.
5. Compare analytical and iterative optimization approaches.

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn

---

## Methodology

### Data Preprocessing

* Missing value imputation
* One-Hot Encoding for categorical variables
* Feature Scaling for Gradient Descent model
* Train-Test Split (75% Training, 25% Testing)

### Models Implemented

#### 1. Standard Linear Regression

Uses the closed-form solution available in Scikit-Learn.

#### 2. Linear Regression using Gradient Descent

Implemented manually using:

* Cost Function (Mean Squared Error)
* Gradient Computation
* Parameter Updates
* Convergence Checking

---

## Results

### Standard Linear Regression

* R² Score: 0.8336
* MAE: 5.9870 minutes
* RMSE: 9.0668 minutes

### Gradient Descent Linear Regression

* R² Score: 0.8336
* MAE: 5.9870 minutes
* RMSE: 9.0668 minutes

### Gradient Descent Information

* Learning Rate: 0.03
* Iterations Completed: 5594
* Initial Cost: 1877.203333
* Final Cost: 59.350368

---

## Performance Comparison

| Metric   | Standard Linear Regression | Gradient Descent |
| -------- | -------------------------- | ---------------- |
| R² Score | 0.8336                     | 0.8336           |
| MAE      | 5.9870                     | 5.9870           |
| RMSE     | 9.0668                     | 9.0668           |

Both approaches achieved identical prediction performance, demonstrating successful convergence of Gradient Descent.

---

## Visualizations

The project generates:

* Actual vs Predicted Delivery Time Plot
* R² Score Comparison Graph
* Gradient Descent Convergence Curve

---

## Conclusion

The Food Delivery Time Prediction model was successfully developed and evaluated. Standard Linear Regression achieved strong predictive performance, while Gradient Descent successfully learned the optimal parameters through iterative optimization.

The identical evaluation metrics obtained from both approaches validate the correctness of the Gradient Descent implementation.

---

## Author

Atharv Fatale

B.Tech Electronics and Telecommunication Engineering

MIT Academy of Engineering, Alandi, Pune
