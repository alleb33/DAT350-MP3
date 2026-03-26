# MP3 Machine Learning Project

## Overview
This project focuses on building and evaluating machine learning models to predict flight prices using a real world dataset. The workflow includes data cleaning, preprocessing, model training, and performance evaluation. The goal is to simulate the role of a machine learning engineer preparing data and selecting models for predictive tasks.

## Dataset
Flight Price Prediction Dataset  
https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction/data

## Problem Type
Regression task where the target variable is flight price.

## Results
Linear Regression  
Training R2 approximately 0.927  
Testing R2 approximately 0.927  
This model showed consistent but lower performance compared to others, indicating slight bias.

Decision Tree  
Training R2 approximately 0.965  
Testing R2 approximately 0.963  
The model demonstrated strong generalization after tuning hyperparameters.

Random Forest  
Training R2 approximately 0.981  
Testing R2 approximately 0.978  
This model achieved the best overall performance with high accuracy and low error.

K Nearest Neighbors  
Training R2 approximately 0.984  
Testing R2 approximately 0.975  
The model performed well but showed slightly higher variance compared to others.

## Bias and Variance Analysis
Linear Regression showed mild bias due to lower overall performance but was consistent between training and testing.

Decision Tree showed a good balance between bias and variance after limiting depth and adjusting parameters.

Random Forest showed excellent generalization with minimal difference between training and testing performance.

KNN showed slight variance as training performance was somewhat better than testing performance.

Overall, none of the models showed severe overfitting or underfitting.

## Conclusion
Random Forest produced the best results overall, balancing high accuracy with strong generalization. All models performed well on the dataset, and the preprocessing pipeline effectively prepared the data for machine learning tasks.
