# Food Demand Forecasting System

## Overview

This project develops a Machine Learning system that predicts food demand using historical order data from multiple fulfillment centers and meal categories.

Accurate demand forecasting helps organizations reduce food waste, optimize inventory management, improve operational efficiency, and enhance customer satisfaction.

---

## Business Problem

Food delivery and distribution organizations must estimate future demand accurately to:

* Reduce food waste
* Improve inventory planning
* Optimize supply chain operations
* Improve resource allocation
* Support business decision-making

---

## Dataset

Dataset Source: Kaggle Food Demand Forecasting Challenge

The dataset contains:

* 456,000+ historical meal orders
* Multiple fulfillment centers
* Meal categories and cuisines
* Pricing information
* Promotional campaign data
* Homepage featured information

Files:

* train.csv
* test.csv
* meal_info.csv
* fulfilment_center_info.csv

---

## Exploratory Data Analysis

Key findings:

* Rice Bowl meals generated the highest average demand.
* Sandwiches and beverages were also strong demand drivers.
* Homepage featured meals received higher demand.
* Promotional emails showed a positive but limited impact.
* Pricing and operational area significantly influenced demand.
* Demand patterns varied across fulfillment centers.

---

## Feature Engineering

Created additional features:

* Discount Amount
* Discount Percentage

Applied One-Hot Encoding to categorical variables:

* Category
* Cuisine
* Center Type

---

## Models Evaluated

| Model             | R² Score |
| ----------------- | -------- |
| Linear Regression | 0.417    |
| Gradient Boosting | 0.667    |
| Random Forest     | 0.855    |
| XGBoost           | 0.871    |

---

## Final Model

XGBoost Regressor

Performance:

* R² Score: 0.871
* MAE: 117.18
* RMSE: 225.40

The XGBoost model achieved the best predictive performance by capturing nonlinear relationships between meal characteristics, pricing, promotions, and fulfillment center attributes.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* Jupyter Notebook

---

## Project Structure

Food-Demand-Forecasting-System/

* data/
* notebooks/
* models/
* images/
* README.md
* requirements.txt

---

## Future Improvements

* Hyperparameter tuning
* Time-series forecasting models
* Real-time demand prediction dashboard
* Cloud deployment
* Automated retraining pipeline

---

## Author

Muhammad Abdullah Hameed

Bachelor of Science in Computer Science (BSCS)

Aspiring Machine Learning Engineer
