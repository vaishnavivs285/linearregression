House Price Prediction using Linear Regression
## PROJECT OVERVIEW

This project predicts house prices based on multiple features such as square footage, number of bedrooms, bathrooms, year built, lot size, garage size, and neighborhood quality.
A Linear Regression model is trained and evaluated to understand how these factors influence house prices.

## TOOLS AND LIBRARIES USED
Python
Pandas
NumPy
Matplotlib / Seaborn
Scikit-Learn

## DATASET DESCRIPTION
 kaggle dataset : https://www.kaggle.com/datasets/prokshitha/home-value-insights
The dataset contains **1000 rows** and **8 columns**:

| Feature | Description |
|-------|------------|
| Square_Footage | Total area of the house |
| Num_Bedrooms | Number of bedrooms |
| Num_Bathrooms | Number of bathrooms |
| Year_Built | Year the house was built |
| Lot_Size | Size of the plot |
| Garage_Size | Number of garage slots |
| Neighborhood_Quality | Quality rating of neighborhood (1–10) |
| House_Price | Target variable (price of the house) |

## Exploratory Data Analysis (EDA)

Checked dataset shape, data types, and missing values
Performed statistical summary
Visualized distribution of house prices
Created a correlation heatmap to understand feature relationships
Strong positive correlation found between Square_Footage and House_Price

## MODEL USED 

Linear Regression (Scikit-Learn)

## MODEL TRAINING STEPS

Selected input features and target variable
Split data into training and testing sets
Trained Linear Regression model on training data
Predicted house prices on test data
Evaluated model performance

## MODEL EVALUATION

The model achieved excellent performance:
MAE: 8,174
RMSE: 10,071
R² Score: 0.998
Indicates the model explains ~99.8% of the variance in house prices.

## PREDICTION
The trained model can be used to predict prices for unseen houses using the learned relationships from the dataset.

## CONCLUSION
The Linear Regression model successfully learned patterns from the data
Predictions closely match actual house prices
This project demonstrates a complete end-to-end regression workflow

## Future Improvements
Feature scaling
Regularization (Ridge / Lasso)
Try advanced models (Random Forest, XGBoost)
Model deployment using Flask / Streamlit
