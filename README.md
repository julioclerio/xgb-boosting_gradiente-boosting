## Overview

This project focuses on predicting customer churn within a banking dataset. Customer churn, also known as customer attrition, refers to the phenomenon where customers stop doing business with a company. The dataset used here contains various attributes and features related to bank customers, aiming to predict whether a customer is likely to leave the bank.

## Directory Structure

- **Notebooks:** This folder contains Jupyter notebooks used for data exploration, model training, and result evaluation. Each regression model has a dedicated notebook for analysis and implementation.

- **Repository:** The `dataset` folder contains the CSV file with the necessary data for training and testing the regression models.

## About this file - Attribute Information

| Attribute | Description |
|-----------|-------------|
| age | Numeric - Age of the client |
| job | Categorical - Type of job (e.g., admin, blue-collar, entrepreneur, etc.) |
| marital | Categorical - Marital status (e.g., divorced, married, single, unknown) |
| education | Categorical - Education level (e.g., basic.4y, high.school, university.degree, unknown) |
| default | Categorical - Has credit in default? (e.g., no, yes, unknown) |
| balance | Numeric - Average yearly balance in euros |
| housing | Categorical - Has housing loan? (e.g., no, yes, unknown) |
| loan | Categorical - Has personal loan? (e.g., no, yes, unknown) |
| contact | Categorical - Contact communication type (e.g., cellular, telephone) |
| day | Numeric - Last contact day of the month (1 - 31) |
| month | Categorical - Last contact month of the year (e.g., jan, feb, mar, ..., nov, dec) |
| duration | Numeric - Last contact duration in seconds (Note: Highly affects the output target) |
| campaign | Numeric - Number of contacts performed during this campaign and for this client |
| pdays | Numeric - Number of days passed since the client was last contacted from a previous campaign (999 means not previously contacted) |
| previous | Numeric - Number of contacts performed before this campaign and for this client |
| poutcome | Categorical - Outcome of the previous marketing campaign (e.g., failure, nonexistent, success) |
| target | Binary - Has the client subscribed a term deposit? (yes, no) |

## Applied Models

- **Grandient Boosting**
- **XGB Boosting**

## XGBoost and Gradient Boosting

### XGBoost (Extreme Gradient Boosting)

XGBoost is an optimized and scalable implementation of gradient boosting. It stands for Extreme Gradient Boosting and is based on the gradient boosting framework, designed for speed and performance. It's widely used in machine learning competitions and data science projects due to its efficiency and accuracy.

#### Key Features of XGBoost:
- **Regularization**: Helps in preventing overfitting by penalizing complex models.
- **Parallelization**: Utilizes parallel computing to enhance training speed.
- **Tree Pruning**: Prunes trees that do not contribute significantly to the model, improving efficiency.
- **Built-in Cross-Validation**: Facilitates model tuning by incorporating cross-validation.

### Gradient Boosting

Gradient boosting is a machine learning technique used for both regression and classification tasks. It works by combining multiple weak predictive models (typically decision trees) to create a strong model. Each new model attempts to correct errors made by the previous one. It's an ensemble technique that builds models sequentially.

#### Key Features of Gradient Boosting:
- **Sequential Learning**: Models are built sequentially, with each new model correcting the errors of its predecessor.
- **Ensemble Method**: Combines multiple weak models to create a robust and accurate model.
- **Gradient Descent**: Optimizes a loss function by moving in the direction of the negative gradient of the loss.

### Advantages in Data Analysis:

Both XGBoost and Gradient Boosting provide several advantages in data analysis:
- **High Predictive Accuracy**: Both methods produce highly accurate predictions.
- **Handle Complex Relationships**: They can capture complex relationships between features and the target variable.
- **Robust to Overfitting**: Incorporating regularization techniques helps prevent overfitting.
- **Feature Importance**: Provide insights into feature importance, aiding in feature selection and understanding the dataset.

In summary, XGBoost and Gradient Boosting are powerful algorithms known for their predictive accuracy and capability to handle complex datasets, making them valuable tools in the field of machine learning and data analysis.

## How to Use

1. Clone this repository to your local environment.
2. The notebooks can be executed in a platform that supports Python and Jupyter Notebooks.
3. Follow the instructions in the notebooks to load the data, train the models, and evaluate the results.


## Getting Started

To get started with this project, clone the repository and navigate to the respective directories to access the Jupyter notebooks and the dataset:

```bash
git clone https://github.com/julioclerio/xgb-boosting_gradiente-boosting

# Run the Jupyter notebooks
cd xgb-boosting_gradiente-boosting/notebooks

# Access the dataset for your analyses
repository/bank-full.csv
