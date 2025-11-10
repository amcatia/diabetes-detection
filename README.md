# Diabetes Detection Project

This project is designed to analyze and predict diabetes using the **Pima Indians Diabetes Dataset**.  
The code is written in Jupyter Notebook and includes the following steps:

- Load the dataset
- Exploratory Data Analysis (EDA)
- Correlation heatmap visualization
- Train a Linear Regression model
- Evaluate the model and calculate accuracy

## How to Run
1. Install the required libraries:
#importing packes and Libreries

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.linear_model import LinearRegression
from sklearn.model_selection import train_test_split
from sklearn.metrics import mean_squared_error, r2_score


2. Run the notebook:
jupyter notebook notebooks/Diabetes.ipynb

## Dataset
The dataset used is the [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database).  
If the file `diabetes.csv` is not included, you can download it from the link above.

## Results
- Feature correlation heatmap
- Model performance metrics
- Accuracy of diabetes prediction
