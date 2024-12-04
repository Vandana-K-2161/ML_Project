# ML_Project
# Car Price Prediction Project 🚗💵  

## Project Overview  
This project aims to predict car prices in the US market using various features. The dataset, provided by a consulting firm, helps a Chinese automobile company understand pricing dynamics to strategically design and price cars.  

## Dataset  
The dataset includes:  
- **Car Specifications**: Engine type, fuel type, horsepower  
- **Performance Metrics**  
- **Price Influencing Features**: Brand, body type  
- **Target Variable**: Price  

## Methodology  
1. **Data Preprocessing**:  
   - Handle missing values.  
   - Remove outliers using the IQR method.  
   - Encode categorical data with one-hot encoding.  
   - Select top features with SelectKBest.  
   - Scale numeric data using StandardScaler.  

2. **Model Implementation**:  
   - Linear Regression  
   - Decision Tree Regressor  
   - **Random Forest Regressor** (Best Model)  
   - Gradient Boosting Regressor  
   - Support Vector Regressor  

3. **Model Evaluation**:  
   - R-squared (R²)  
   - Mean Squared Error (MSE)  
   - Mean Absolute Error (MAE)  

## Best Model  
The **Gradient Boosting Regressor** was identified as the best model

