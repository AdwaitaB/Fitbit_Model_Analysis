# Fitbit_Model_Analysis
This project focuses on analyzing Fitbit activity data and predicting calories burned using linear regression. The dataset includes key fitness metrics such as Total Distance, Active Hours, and Sedentary Hours, which are used to estimate calorie expenditure.

Key Features & Workflow:
1. Data Preprocessing:

Load and inspect the dataset.
Remove invalid or incomplete entries.
Compute Calories Burned using a derived formula based on activity levels.

2. Feature Selection & Splitting:

Select Total Distance, Total Active Hours, and Sedentary Hours as input features.
Use Calories Burned as the target variable.

3. Data Scaling & Model Training:

Standardize input features using StandardScaler.
Train a Linear Regression Model to learn calorie expenditure patterns.

4. Model Evaluation:

Predict calories burned on test data.
Calculate Mean Absolute Error (MAE) and Mean Squared Error (MSE) to assess model accuracy.

5. Prediction on New Data
