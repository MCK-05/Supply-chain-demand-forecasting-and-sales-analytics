# Supply Chain demand forecasting and sales analytics

## Project Overview
This project aims to optimize the supply chain by predicting weekly sales for various stores using a machine learning approach. We used RandomForestRegressor to model the sales data based on features such as store characteristics, promotions, and external factors. This project provides insights into the drivers of sales and helps in making data-driven decisions for optimizing inventory and supply chain operations.

## Objective
The objective of this project is to predict the `Weekly_Sales` for retail stores using historical data, including features such as promotions, store type, holidays, and seasonal factors. By developing a machine learning model, we aim to:

1. Provide accurate sales predictions for inventory management.
2. Analyze the importance of different features in predicting sales.
3. Visualize sales trends and key metrics to derive insights.

## Dataset
The project uses four datasets:

1. **Features.csv**: Contains additional information about the stores, such as promotional events and weather conditions.
2. **Stores.csv**: Contains store-related information, including store type and assortment type.
3. **Train.csv**: Historical sales data for training the model, including `Weekly_Sales` for each store.
4. **Test.csv**: Test data for evaluating the model.


## Tools and Technologies
- **Python**: Core language used for analysis and modeling.
- **Pandas**: For data manipulation and preprocessing.
- **Scikit-Learn**: For machine learning modeling and evaluation.
- **Seaborn and Plotly**: For data visualization.
- **Matplotlib**: For plotting basic visualizations.


## Results
- **Mean Squared Error (MSE)**: The error metric used to measure the average squared difference between predicted and actual sales.
- **R-squared (R²)**: Indicates how well the features explain the variance in sales.
<img width="1366" height="655" alt="Figure_1" src="https://github.com/user-attachments/assets/3870ca3c-9741-484c-ad69-a08e9365771b" />
Mean Squared Error: 12007306.061619846
R-squared: 0.9769090605697065
The model achieved reasonable accuracy in predicting weekly sales, with the feature importance analysis highlighting key drivers of sales such as promotions, store type, and seasonal factors.



