# Movie Rating Prediction

## Overview
This project predicts the **rating of a movie** based on features such as **Genre**, **Director**, and **Actors** using Machine Learning regression models. The project performs data preprocessing, label encoding of categorical features, and trains regression models to estimate movie ratings.

## Dataset
- Dataset: IMDb Movies India Dataset
- Target Variable: Rating
- Features include:
  - Genre
  - Director
  - Actor 1
  - Actor 2
  - Actor 3

## Project Workflow
1. Import required libraries
2. Load the dataset
3. Explore and analyze the data
4. Handle missing values
5. Encode categorical features using LabelEncoder
6. Select input features and target variable
7. Split the dataset into training and testing sets
8. Train Linear Regression model
9. Train Random Forest Regressor model
10. Evaluate model performance using regression metrics
11. Compare actual and predicted ratings
12. Visualize predictions and feature importance

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Models Used
- Linear Regression
- Random Forest Regressor

## Evaluation Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## Results
- Linear Regression serves as the baseline model.
- Random Forest Regressor generally provides better prediction accuracy by capturing complex relationships between movie features and ratings.
- The project also displays feature importance and a comparison of actual versus predicted movie ratings.

## How to Run
1. Clone the repository.
2. Install the required libraries.
3. Open the Jupyter Notebook.
4. Ensure `IMDb Movies India.csv` is present in the project directory.
5. Run all cells.

## Author
Sankalp Sharma
