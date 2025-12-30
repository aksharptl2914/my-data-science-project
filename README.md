\# Customer Churn Prediction



\## Business Problem

Customer churn directly impacts revenue.  

This project builds a machine learning pipeline to predict churn and identify the strongest behavioral drivers.



\## Data

Public customer churn dataset with demographic, service usage, and contract features.



\## Approach

1\. Exploratory Data Analysis (EDA)

2\. Data cleaning and feature engineering

3\. Baseline logistic regression

4\. Model evaluation using ROC-AUC and F1-score



\## Results

\- ROC-AUC: 0.82

\- F1-score: 0.74

\- Key churn drivers: contract type, tenure, monthly charges



\## Repo Structure

\- `notebooks/`: EDA and visualization

\- `src/`: reusable pipeline code

\- `reports/figures/`: charts used in this README



\## How to Run

```bash

pip install -r requirements.txt

python src/main.py



