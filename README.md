# Lab 1: Introduction to Linear Regression with One Variable

**Authors:** Àlex Font Bartumeus and Iris Azlor Solé

## Overview
This project builds a simple linear regression model with one variable. The goal is to predict how many days a patient will stay in the hospital based on their age. This helps hospitals plan and manage their resources better.

## Dataset
* **File:** `synthetic_patients.txt`
* **Size:** 500 patient records with 2 columns (age and days in the hospital)
* **Data Split:** 400 records for training the model and 100 records for testing it

## Project Steps
1. **Problem Formulation:** Define the goal of predicting hospital stay duration using patient age.
2. **Data Loading & Splitting:** Load the dataset and divide it into training and test sets.
3. **Data Visualization:** Create histograms for both variables and a scatter plot to see the linear relationship between age and stay duration.
4. **Matrix Representation & Gradient Descent:** 
   * Build design matrices by adding a column of ones for the intercept term.
   * Implement the Mean Squared Error (MSE) loss function.
   * Train the model using the Gradient Descent algorithm for 200 iterations with a learning rate of `1e-5`.
5. **Model Evaluation:** Test the model with new age examples, plot the fitted regression line, and compare the model's error against a baseline.

## Results
* **Learned Parameters ($\theta$):** Approximately `[0.0102, 0.5354]`
* **Example Predictions:** 
  * A 58-year-old patient is predicted to stay about **31.06 days**.
  * A 25-year-old patient is predicted to stay about **13.39 days**.
* **Performance (Mean Absolute Error):** 
  * **Model MAE:** 4.68
  * **Baseline MAE:** 7.23

## How to Run
1. Make sure you have **Python** and **Jupyter Notebook** installed.
2. Keep the `synthetic_patients.txt` file in the same folder as the notebook.
3. Open the `.ipynb` file in Jupyter Notebook and run all cells from top to bottom.
