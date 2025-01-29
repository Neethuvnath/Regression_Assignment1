# Regression_Assignment1
Code Explanation
Step 1: Import Libraries
Includes all necessary libraries for data loading, preprocessing, training, evaluation, and visualization.

Step 2: Load Dataset
Uses fetch_california_housing to load the dataset and convert it into a pandas DataFrame.

Step 3: Preprocessing
Missing values are filled with column medians (although the dataset usually has no missing values).
Standardization is performed using StandardScaler.
Step 4: Train-Test Split
Splits the data into 80% training and 20% testing.

Step 5: Initialize Models
Includes five regression models:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
Support Vector Regressor (SVR)
Step 6: Train and Evaluate Models
Each model is trained, and the following metrics are calculated on the test set:

Mean Squared Error (MSE)
Mean Absolute Error (MAE)
R-squared Score (R²)

Step 7: Identify Best and Worst Model
The best and worst models are identified based on the R² score.
