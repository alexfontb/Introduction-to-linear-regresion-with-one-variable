# Lab 1: Introduction to Linear Regression with One Variable

**Authors:** Àlex Font Bartumeus and Iris Azlor Solé

## Overview
This project builds a simple linear regression model with one variable. The goal is to predict how many days a patient will stay in the hospital based on their age[cite: 3]. This helps hospitals plan and manage their resources better[cite: 3].

## Dataset
* **File:** `synthetic_patients.txt`[cite: 3]
* **Size:** 500 patient records with 2 columns (age and days in the hospital)[cite: 3]
* **Data Split:** 400 records for training the model and 100 records for testing it[cite: 3]

## Project Steps
1. **Problem Formulation:** Define the goal of predicting hospital stay duration using patient age[cite: 3].
2. **Data Loading & Splitting:** Load the dataset and divide it into training and test sets[cite: 3].
3. **Data Visualization:** Create histograms for both variables and a scatter plot to see the linear relationship between age and stay duration[cite: 3].
4. **Matrix Representation & Gradient Descent:** 
   * Build design matrices by adding a column of ones for the intercept term[cite: 3].
   * Implement the Mean Squared Error (MSE) loss function[cite: 3].
   * Train the model using the Gradient Descent algorithm for 200 iterations with a learning rate of `1e-5`[cite: 3].
5. **Model Evaluation:** Test the model with new age examples, plot the fitted regression line, and compare the model's error against a baseline[cite: 3].

## Results
* **Learned Parameters ($\theta$):** Approximately `[0.0102, 0.5354]`[cite: 3]
* **Example Predictions:** 
  * A 58-year-old patient is predicted to stay about **31.06 days**[cite: 3].
  * A 25-year-old patient is predicted to stay about **13.39 days**[cite: 3].
* **Performance (Mean Absolute Error):** 
  * **Model MAE:** 4.68[cite: 3]
  * **Baseline MAE:** 7.23[cite: 3]

## How to Run
1. Make sure you have **Python** and **Jupyter Notebook** installed.
2. Keep the `synthetic_patients.txt` file in the same folder as the notebook[cite: 3].
3. Open the `.ipynb` file in Jupyter Notebook and run all cells from top to bottom.
