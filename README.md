# Advertising Sales Prediction

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)

## About the Project

This project is part of my Machine Learning learning journey. I built three Simple Linear Regression models using Python and Scikit-learn to predict product sales based on different advertising channels.

The main objective was to understand the complete machine learning workflow, including data preparation, model training, visualization, evaluation, and performance comparison.

## Objective

In this project, I trained three separate models to predict **Sales** using one feature at a time:

- TV Advertising
- Radio Advertising
- Newspaper Advertising

After training the models, I compared their performance using different evaluation metrics to determine which advertising channel is the best predictor of sales.

## Dataset

**Dataset:** Advertising Dataset

Features:
- TV Advertising
- Radio Advertising
- Newspaper Advertising

Target:
- Sales

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Project Workflow
1. Load the dataset using Pandas.
2. Select the input feature for single feature regression.
3. Split the dataset into training and testing sets (`train_test_split`).
4. Train a Simple Linear Regression model (`LinearRegression`).
5. Predict the test set results.
6. Visualize the regression line using Matplotlib.
7. Evaluate model performance using:
   - **Mean Squared Error (MSE)**
   - **Root Mean Squared Error (RMSE)**
   - **$R^2$ Score**
8. Compare the performance of all three models using comparative tables and bar charts.
   
## Results & Summary

After evaluating the three models on the test dataset:

- The **TV advertising model** achieved the highest $R^2$ Score.
- The **TV advertising model** produced the lowest MSE and RMSE.
- The **Newspaper advertising model** showed the weakest performance among all three.

### Conclusion
Based on the metrics, **TV advertising** is the strongest single feature for predicting sales when using Simple Linear Regression.

## Author
**Khaled Amireh**  
