# Credit Card Fraud Detection

## Overview
This project predicts whether a credit card transaction is **Fraudulent** or **Legitimate** using Machine Learning. A Logistic Regression model is trained on the Credit Card Fraud Detection dataset after performing data preprocessing and handling class imbalance through Random Under-Sampling.

## Dataset
- Dataset: Credit Card Fraud Detection Dataset
- Target Variable: Class
  - 0 → Legitimate Transaction
  - 1 → Fraudulent Transaction
- Features include:
  - Time
  - V1 to V28 (PCA transformed features)
  - Amount

## Project Workflow
1. Import libraries
2. Load dataset
3. Explore and analyze the data
4. Check class distribution
5. Handle imbalanced data using Random Under-Sampling
6. Split dataset into training and testing sets
7. Train Logistic Regression model
8. Evaluate model accuracy

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn

## Results
- Model: Logistic Regression
- Evaluation Metric: Accuracy Score
- The model successfully classifies transactions as legitimate or fraudulent after balancing the dataset using Random Under-Sampling.

## How to Run
1. Clone the repository.
2. Install the required libraries.
3. Open the Jupyter Notebook.
4. Ensure `creditcard.csv` is present in the project directory.
5. Run all cells.

## Author
Sankalp Sharma
