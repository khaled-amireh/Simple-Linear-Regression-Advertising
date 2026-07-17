# Simple Linear Regression Using the Advertising Dataset

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
- Jupyter Notebook

## Project Workflow

1. Load the dataset.
2. Select the input feature.
3. Split the dataset into training and testing sets.
4. Train a Simple Linear Regression model.
5. Predict the test set results.
6. Visualize the regression line.
7. Evaluate the model using:
   - Mean Squared Error (MSE)
   - Root Mean Squared Error (RMSE)
   - R² Score
8. Compare the performance of the three models using tables and bar charts.

## Results

After evaluating the three models, I found that:

- The TV advertising model achieved the highest R² Score.
- The TV advertising model produced the lowest MSE.
- The TV advertising model produced the lowest RMSE.
- The Newspaper advertising model showed the weakest performance.

Based on these results, TV advertising is the strongest single feature for predicting sales using Simple Linear Regression.

## Repository Structure

```
Machine-Learning-Projects/
│
├── Advertising.csv
├── Simple_Linear_Regression_Project.ipynb
└── README.md
```

## Author

Khaled Amireh
ِق
