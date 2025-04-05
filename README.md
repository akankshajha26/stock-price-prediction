#Stock Price Prediction

This project aims to predict stock prices using historical data and key technical indicators. I focused on implementing a clean and effective machine learning workflow using Linear Regression, which surprisingly outperformed more complex models like Random Forest and XGBoost for this dataset.

Objective

The goal was to:

Fetch historical stock data using yfinance

Engineer meaningful features like EMAs and RSI

Train and evaluate regression models to predict 'Close' prices

Compare model performance and select the best one

Features Used

50-day EMA

200-day EMA

RSI (Relative Strength Index)

High

Volume

After checking feature correlation, I dropped highly correlated ones like Open, Low, and Bollinger Bands.

Models Tried

Linear Regression (best performing)

Random Forest Regressor

XGBoost Regressor

Despite being simpler, Linear Regression gave the best performance in this case, possibly due to the clean and linear nature of the processed data.

Visualizations

RSI trends

Price along with 50/200-day EMAs

Actual vs Predicted scatter plot

These helped in understanding the stock movement patterns and model performance visually.

Libraries Used

yfinance

pandas, numpy

matplotlib, seaborn

scikit-learn

Final Thoughts

This project helped reinforce my understanding of:

Time-series feature engineering

Importance of feature selection

How simpler models can sometimes outperform complex ones
