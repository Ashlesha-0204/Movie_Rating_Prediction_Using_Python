# Movie_Rating_Prediction_Using_Python

## Overview
The **Movie Rating Prediction** project aims to build a machine learning model that predicts movie ratings based on key features such as genre, director, and actors. This project leverages regression techniques to analyze historical data and develop an accurate predictive model. It also provides insights into factors influencing movie ratings while showcasing data preprocessing, feature engineering, and modeling techniques.

## Key Features of the Project

### Machine Learning Algorithms
- **Linear Regression (OLS):** Baseline regression model for predicting ratings.
- **Random Forest Regressor:** Ensemble learning method for improved accuracy.
- **Decision Tree Regressor:** Simple, interpretable regression model.

### Data Preprocessing Techniques
- **StandardScaler:** Used for scaling numerical features to standardize their ranges.
- **Label Encoding:** Applied to categorical variables for numerical representation.

### Feature Engineering
- **Target Encoding:** Performed using K-Fold Cross-Validation to encode high-cardinality categorical features like:
  - Genre
  - Director
  - Actor 1, Actor 2, Actor 3
- **Variance Inflation Factor (VIF) Analysis:** Used to detect and address multicollinearity issues.

### Train-Test Split
- Splitting the dataset into training and testing sets using **train_test_split** for model validation.

### Model Evaluation Metrics
- **R² Score:** Measures the proportion of variance explained by the model.
- **Root Mean Squared Error (RMSE):** Square root of MSE, providing an interpretable error metric.


