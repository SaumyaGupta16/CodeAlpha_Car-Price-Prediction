# Car Price Prediction

This project predicts the selling price of used cars based on various attributes like present price, mileage, fuel type, and car age. It applies machine learning techniques to build a robust regression model.

## Dataset
The dataset contains details of used cars including:
- Year of purchase
- Present price
- Kilometers driven
- Fuel type
- Transmission type
- Seller type
- Ownership history
- Selling price (target variable)

## Project Workflow
- Data inspection and preprocessing
- Feature engineering (Car_Age from Year)
- Categorical variable encoding
- Exploratory Data Analysis (EDA) with correlation heatmap
- Model training:
  - Random Forest Regressor
  - Linear Regression (for comparison)
- Model evaluation (R² Score, RMSE)
- Feature importance analysis
- Visualizations: Actual vs Predicted plots, feature importance

## Results

| Model              | R² Score | RMSE   |
|-------------------|----------|--------|
| Random Forest      | ~0.96    | ~0.92  |
| Linear Regression  | ~0.86+   | Higher |

## Visualizations
- Correlation heatmap
- Feature importance bar plot
- Actual vs Predicted price scatter plot

## Conclusion
Random Forest performed significantly better in predicting car selling prices. Feature engineering (especially using car age) and encoding played a key role in improving model accuracy.
