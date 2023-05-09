# Electricity Price Forecasting using Machine Learning

This project aims to create an accurate and efficient electricity price forecasting model to improve traders' profit margins by using various machine learning techniques. The forecasting process is divided into four stages: data imputation, feature scaling, feature selection, and model training and selection. An ensemble of low bias high variance models with an input window size of 24 hours provided measurable improvement to the mean absolute error benchmark over all the 35 nodes.

## Stages
1. Data Imputation
2. Feature Scaling
3. Feature Selection
4. Model Training and Selection

## Techniques Tested
- Min-Max scaling
- Proposed feature selection strategy
- Support Vector Regression (SVR)
- Deep learning models (e.g., TCNN, CNN, BiLSTM)
- Ensemble of low bias high variance models

## Results
- Mean Absolute Error (MAE) reduced by 13% using the proposed method.
- SVR outperformed deep networks on average, but deep networks excelled in certain cases.
- Outlier engineering and removal of weekends and work hours improved the forecast.

## Future Work
- Investigate very short-term price forecasts.
- Consider advanced imputation techniques for large amounts of missing data.

## Funding and Acknowledgment
This work was funded by Solea Energy through CBL, an NSF IUCRC. Dr. Derakhshani is also a consultant for Jumio.
