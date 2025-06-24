# Credit Risk Prediction using Machine Learning

This project analyzes and predicts the likelihood of a credit card customer defaulting using the UCI Credit Card Default dataset.

## Objective

To compare traditional statistical modeling (Logistic Regression) with modern machine learning models (Random Forest and XGBoost) in classifying credit risk.

## Dataset

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients)
- 30,000 customer records
- Features: Demographics, credit limits, payment history, billing amount
- Target: `default.payment.next.month` (1 = Default, 0 = No Default)

## Models Used

- Logistic Regression
- Random Forest
- XGBoost

## Visualizations

- Top 10 Feature Importances (XGBoost)
- LIMIT_BAL distribution by default status
- PAY_0 vs default countplot

## Folder Structure
notebooks/ # Main modeling notebook
data/ # Dataset
images/ # Visuals used in Medium or report


## Getting Started

1. Clone the repository
2. Install requirements:  
    ```
    pip install -r requirements.txt
    ```
3. Run the notebook inside `/notebooks/`

## Requirements

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost



