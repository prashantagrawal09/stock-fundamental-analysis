# Stock Fundamental Analysis

## Intro & Problem Statement
With the advent of digital banking services and brokerages offering easy access to retail trading over the past years, the stock market has seen an influx of many first-time investors from the retail sector. Given so, most investors who are inexperienced or uninformed usually make poor decisions with their investments, resulting in losses.

This project seeks to create a data driven approach to selecting stocks based on fundamental data, and removes all price related data. We have taken the stance that past price patterns cannot predict future prices -- the same way you cannot drive a car looking through the rear view mirror!

## Approach
Analyse which stocks in the S&P 500 would be profitable / valuable in the long run based on current fundamental data.

1. By future price prediction (Numeric Prediction)
2. By clustering of stocks into profitable portfolios (Structure Detection)
   
## File Structure
1. DataScripts contain the python scripts used to save data from AlphaVantage API
2. tickers.csv contain the tickers of the 500 companies in the S&P 500.
3. output.csv contain the data retrieved from AlphaVantage API
4. vol5years contain yearly volatility data
5. yoy5years contain yearly Year-on-Year returns data
6. DSAI_Final.ipynb contain the python notebook where we perform EDA, Machine Learning and Analysis.

## Dataset used
1. AlphaVantage API for stock prices, income statements, balance sheets, statement of cashflows and company overview
2. YahooFinance for stock prices

## Machine Learning Techniques
1. Feature Selection
      a. Standard Scaler
      b. KNN Imputer
      c. Gradient Boosting Regressor

2. Hyperparameter Optimisation
      a. GridSearchCV

3. Supervised Learning
      a. Linear Regression
      b. Lasso Regression
      c. Ridge Regression
      d. Artifical Neural Network

4. Unsupervised Learning
      a.Agglomerative Clustering
