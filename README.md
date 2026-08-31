# Credit Card Default Prediction

Machine learning classification project focused on predicting whether a credit card customer will default based on credit limits, repayment history, billing behaviour, payments, and customer characteristics.

## Project Objective

The goal of this project was to build an interpretable model that estimates a customer's probability of default and identifies the factors most strongly associated with credit risk.

## What I Did

- Cleaned and prepared a credit card customer dataset containing 30,000 observations
- Explored customer demographics, credit limits, repayment status, bill amounts, and payment history
- Prepared categorical and numerical variables for modelling
- Split the data into training and test sets
- Built a Logistic Regression classification model
- Generated probability-of-default estimates
- Evaluated model performance using classification metrics, confusion matrices, ROC curves, and precision-recall analysis
- Examined model coefficients to understand which variables were associated with higher or lower default risk

## Dataset

The dataset contains customer-level credit information including:

- Credit limit
- Age
- Education
- Marital status
- Historical repayment status
- Monthly bill amounts
- Previous payment amounts
- Default outcome

The target variable identifies whether a customer defaulted on their credit card payment.

## Technologies

Python, Pandas, NumPy, scikit-learn, Logistic Regression, Matplotlib

## Files

- `credit_card_default_prediction.ipynb` – data preparation, modelling, evaluation, and interpretation
- `Credit Card Defaulter Prediction.csv` – source dataset used to train and evaluate the model

## Running the Project

1. Download this repository
2. Keep `Credit Card Defaulter Prediction.csv` in the same folder as the notebook
3. Open `credit_card_default_prediction.ipynb`
4. Run the notebook from top to bottom

The notebook automatically checks for the dataset in the current directory before loading it.
## Project Context

This project was completed as part of graduate analytics coursework at Smith School of Business, Queen's University.
## Project Context

This project was completed as part of graduate analytics coursework at Smith School of Business, Queen's University.
