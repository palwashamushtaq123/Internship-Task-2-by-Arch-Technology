# **Stock Price Prediction Using Machine Learning**

**Project Overview**

This project focuses on predicting stock closing prices using Machine Learning techniques and historical stock market data.
The dataset contains 12,069 observations and 14 features, including important stock market indicators such as:

- Open Price
- High Price
- Low Price
- Close Price
- Volume
- Sentiment-based variables

**The objective of this project was to build a predictive model capable of estimating stock closing prices with minimal error.**

**Data Preprocessing**

To improve model performance and ensure data quality:
- Irrelevant columns were removed
- Text-based features were excluded
- Numerical features were selected for model training
- Missing and unnecessary information was cleaned

**Machine Learning Model**

A Linear Regression model was trained using the following input features:
- Open
- High
- Low
- Volume

**Target Variable:**
- Close Price

**The dataset was divided into:**

- Training Set
- Testing Set

to evaluate prediction performance effectively.

**Model Performance**

The model achieved strong prediction results on test data:
- Metric	Value
- MAE (Mean Absolute Error)	1.17
- MSE (Mean Squared Error)	2.85

**Performance Insights**
- Low prediction error indicates reliable model behavior
- Predicted values closely followed actual stock prices
- The model successfully captured market trends and short-term volatility
  
**Visualization & Analysis**

Visual analysis confirmed that:

- Predicted stock prices strongly overlap with actual values
- Trend movement was accurately captured
- Minimal deviation exists between real and predicted prices

**These results demonstrate the effectiveness of Linear Regression for short-term stock price estimation.**

**Final Conclusion**

The Stock Price Prediction model showed strong predictive capability using historical numerical market data.

The project highlights:

- Effective preprocessing techniques
- Importance of feature selection
- Application of regression models in financial forecasting
- Ability of Linear Regression to capture stock market trends with good accuracy

**Overall, the model provided reliable and stable predictions for stock closing prices.**

**Future Enhancements**
- Implement advanced models such as Random Forest Regressor, XGBoost, or LSTM
- Add technical indicators (RSI, Moving Average, MACD)
- Improve prediction accuracy using time-series forecasting techniques
- Explore deep learning approaches for sequential stock data

**Project Files**
- Jupyter Notebook
- A detail Ppt Report

**Learning Outcomes**

Through this project, I learned:
- Financial data preprocessing
- Regression modeling techniques
- Model evaluation using MAE & MSE\
- Trend analysis and visualization
- Real-world application of Machine Learning in finance
