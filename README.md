# CodeAlpha: Car Price Prediction

This repository contains my submission for **Task 3: Car Price Prediction with Machine Learning** as part of the Data Science Internship at CodeAlpha.

## Project Overview
The objective of this project is to build a machine learning model capable of predicting the future resale selling price of a used car based on several features like its current showroom price, kilometers driven, fuel type, transmission, type of seller, and age.

## Features Analyzed:
* **Present_Price:** Current showroom price of the car (in Lakhs)
* **Driven_kms:** Total distance the car has traveled
* **Fuel_Type:** Petrol, Diesel, or CNG
* **Selling_type:** Dealer or Individual seller
* **Transmission:** Manual or Automatic
* **Year:** The manufacturing year (used to calculate vehicle age)

## Technologies and Libraries Used
* **Python** (Programming Language)
* **Jupyter Notebook** (Development Environment)
* **Pandas & NumPy** (Data Exploration and Cleaning)
* **Matplotlib & Seaborn** (Data Visualization)
* **Scikit-Learn** (Pipelines, ColumnTransformers, and Random Forest Regression)

## Workflow & Model Performance
1. **Data Preprocessing Pipeline:** Created an end-to-end `Pipeline` that isolates categorical features, automatically processes text columns using `OneHotEncoder`, and standardizes numerical dimensions via `StandardScaler`.
2. **Model Training:** Split the data into an 80/20 train-test ratio and trained a **Random Forest Regressor** with 100 estimator decision trees.
3. **Evaluation Metrics:** The model achieved excellent predictive metrics on the validation set:
   * **Mean Absolute Error (MAE):** Low deviation, indicating high prediction precision.
   * **R-squared ($R^2$) Accuracy Score:** ~96.41% of variance explained by the model.

## How to Run the Project
1. Clone this repository:
   ```bash
   git clone [https://github.com/soundaryaarage8-creator/CodeAlpha_Car_Price_Prediction.git](https://github.com/soundaryaarage8-creator/CodeAlpha_Car_Price_Prediction.git)
