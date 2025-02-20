# Linear Regression Model for Predicting Height from Weight

## Overview
This project demonstrates the implementation of a simple linear regression model to predict height based on weight. The dataset consists of weight and height values, and we apply machine learning techniques to train, evaluate, and visualize the model's performance.

## Dataset
The dataset used in this project is `height-weight.csv`, which contains:
- **Weight** (independent variable)
- **Height** (dependent variable)

## Requirements
Ensure you have the following libraries installed before running the code:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Steps Involved

### 1. Importing Necessary Libraries
We import essential libraries such as NumPy, Pandas, Matplotlib, Seaborn, and Scikit-learn for data handling, visualization, and modeling.

### 2. Load and Explore the Dataset
- Read the dataset using Pandas
- Display the first few rows using `df.head()`
- Check dataset shape, data types, and missing values
- Identify duplicate entries

### 3. Data Visualization
- Scatter plot to observe the relationship between weight and height

### 4. Data Preprocessing
- Split data into independent (`X`) and dependent (`y`) variables
- Divide data into training and test sets (80%-20% split)
- Standardize the data using `StandardScaler`

### 5. Model Training
- Train a **Linear Regression** model using the training dataset
- Print model coefficients and intercept

### 6. Model Evaluation
- Predict test set values
- Calculate performance metrics:
  - **Mean Squared Error (MSE)**
  - **Mean Absolute Error (MAE)**
  - **Root Mean Squared Error (RMSE)**
  - **R-squared (R²)**

### 7. Visualization
- Plot best-fit regression line on training and test data
- Plot distribution of residuals using `sns.displot()`
- Plot scatter of residuals vs predicted values

### 8. Prediction for a New Weight
- Predict height for a given new weight value (e.g., 80 kg)

## Results
- Model Coefficients: `[17.03440872]`
- Model Intercept: `157.5`
- **Performance Metrics:**
  - MSE: `109.77`
  - MAE: `9.82`
  - RMSE: `10.47`
  - R²: `0.7769`

## Visualizations
1. **Scatter Plot:** Weight vs Height
2. **Regression Line:** Best fit line for training and test data
3. **Residual Plot:** Residuals distribution
4. **Prediction Scatter Plot:** Predictions vs Actual values

## How to Use
Run the script in a Jupyter Notebook or a Python environment to see the analysis and model performance.

## Author
Developed for educational purposes.
