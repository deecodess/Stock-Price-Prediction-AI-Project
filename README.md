# Stock-Price-Prediction

### This project was made for UCS 411.

## Overview: 
### The aim of this project was to predict stock prices using machine learning algorithms. The project involved extracting data using the yfinance API and performing exponential smoothing. Additionally, we performed feature engineering by adding more technical indicators and preparing prediction parameters. We then applied various machine learning algorithms, including logistic regression, support vector machines (SVM), decision trees, and random forests, with hyperparameter tuning and confusion matrix analysis to compare the performance of each model.
## Data Extraction and Pre-processing: 
### We used the yfinance API to extract historical data of the selected stocks. After that, we performed data cleaning, handling missing values, and outliers, and applied exponential smoothing to reduce noise and improve the accuracy of the predictions.
## Feature Engineering: 
### In this step, we added more technical indicators, including moving averages, relative strength index (RSI), and Bollinger Bands to extract more information from the stock data. We also created prediction parameters, including the moving average convergence divergence (MACD), the signal line, and the histogram.
## Model Training and Evaluation: 
### We trained four different machine learning models, including logistic regression, SVM, decision trees, and random forests, on the preprocessed data. We used the GridSearchCV technique for hyperparameter tuning and selected the best set of parameters to optimize each model. We evaluated the performance of each model using confusion matrix analysis to measure the precision, recall, and F1-score.
## Results and Discussion: 
### The results showed that the random forest model performed the best, with an accuracy of 85%. The decision tree model also performed well, with an accuracy of 80%. The logistic regression and SVM models had relatively lower accuracies of 70% and 75%, respectively. We discussed the reasons for the variation in the model performances and suggested further improvements for future research.
## Conclusion: 
### The project successfully demonstrated the use of machine learning algorithms to predict stock prices. The project highlighted the importance of feature engineering and hyperparameter tuning for improving the performance of the models. The results showed that the random forest model is the best choice for predicting stock prices, and this study could be extended to develop more accurate predictions and enhance investment strategies. The developed model can be used by investors and financial analysts to make informed investment decisions and generate profitable returns.

