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
credit-risk-analysis/
│
├── data/
│   ├── UCI_Credit_Card.csv.zip                # Original dataset (UCI Taiwan Credit Card)
│   └── UCI_Credit_Card.csv                    # Unzipped original dataset
│
├── images/
│   ├── boxplot_limitball_default.png 
|   └── ROC Curve Comparison.png
|   └── countplot_default_pay0.png                  
|   └── top10_features_importances.png                  
│
├── notebooks/
│   ├── credit_risk_model_comparison.ipynb      
│
├── requirements.txt                         # Python dependencies
└── README.md                                # Project overview and instructions



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



