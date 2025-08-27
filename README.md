# Student_Performance

Project Overview
This project explores the Student_Performance.csv dataset to determine the most effective machine learning model for predicting student performance. I implemented and compared four different regression and classification models to identify the key factors influencing academic success.

My Approach
Data Preprocessing: I started by cleaning the data. This included removing duplicates, converting text-based columns into numbers, and standardizing the column names for easier use.

Model Implementation: I built and evaluated the following models:

Simple Linear Regression

Multiple Linear Regression

Polynomial Regression

Logistic Regression

Evaluation: I compared the models using key metrics like Mean Squared Error (MSE) and R-squared (R²) to measure their accuracy and error rates.

Key Findings 
The Multiple Linear Regression model was the most successful, achieving an outstanding R² score of 0.99. This model, which uses both Previous_Scores and Hours_Studied as predictors, proved to be the most accurate for predicting student performance in this dataset.

How to Use This Repository
Clone the repository to your local machine.

Install the required libraries:

pandas

numpy

scikit-learn

matplotlib

seaborn

Explore the analysis: The full step-by-step process, including code and visualizations, is detailed in the Jupyter Notebook ML1.ipynb. The ml1.py file contains the Python script version of the code.
