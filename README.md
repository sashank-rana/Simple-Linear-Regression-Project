# Simple-Linear-Regression-Project

A machine learning project built in Python using Scikit-Learn to model and analyze the linear relationship between monthly sales and advertising expenditures for a dietary weight control product.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset & Features](#dataset--features)
- [Project Workflow](#project-workflow)
- [Getting Started](#getting-started)
- [Running the Code](#running-the-code)
- [Results & Evaluation](#results--evaluation)

## Project Overview
Understanding how advertising budget impacts sales is crucial for optimizing marketing expenditures. This project applies Ordinary Least Squares (OLS) simple linear regression to predict monthly sales based on advertising investments.

## Project Workflow
1. **Exploratory Data Analysis (EDA):** Inspected data distributions, summary statistics, and bivariate scatter plots to confirm linear assumptions.
2. **Model Training:** Utilized `scikit-learn` to fit an Ordinary Least Squares linear regression model.
3. **Residual Analysis:** Examined residuals to test for homoscedasticity and normality of errors.
4. **Diagnostics:** Checked for underfitting and evaluated performance using standard regression metrics ($R^2$, RMSE, MAE).

## Getting Started

### Prerequisites
Make sure you have Python installed along with the required libraries:
\`\`\`bash
pip install numpy pandas scikit-learn matplotlib seaborn jupyter
\`\`\`

## Running the Code

### 1. Locally via Jupyter Notebook
Clone the repository and launch Jupyter Notebook:
\`\`\`bash
git clone https://github.com/sashank-rana/Simple-Linear-Regression-Project.git
cd Simple-Linear-Regression-Project
jupyter notebook
\`\`\`
Open the Jupyter notebook file from your browser dashboard and execute the cells sequentially.

### 2. Via Google Colab
Alternatively, you can upload the `.ipynb` notebook file directly to [Google Colab](https://colab.research.google.com/) to run it instantly in your browser without installing packages locally.

## Author
[Sashank Rana](https://github.com/sashank-rana)
