PRODIGY Internship - Machine Learning

Task 1

House Price Prediction
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Project Overview:

The House Price Prediction project aims to implement a Linear Regression model to predict House prices based on square footage, the number of bedrooms and the number of bathrooms. The dataset consists of training and test data with 81 and 80 columns, respectively.

Data Preprocessing:

The initial phase of the project focuses on data preprocessing. This involves managing missing values in different columns through either substitution with relevant values or employing imputation techniques. Furthermore, categorical columns are transformed using one-hot encoding and the entire dataset is standardized for consistency.

Model Selection:

Three regression models are implemented and evaluated: Lasso, Ridge, and ElasticNet.

Lasso Regression: The Lasso model initially showed a train score of 0.0 and a test score of -0.004, indicating poor performance. Hyperparameter tuning determined the best alpha value (0.01), improving the test score to 0.87. Model evaluation on the test data resulted in an R-squared score of 0.8698.

Ridge Regression: The Ridge model performed well from the beginning, with a train score of 0.93 and a test score of 0.88. Hyperparameter tuning found the best alpha value (15) and maintained a high test score of 0.88. Model evaluation on the test data resulted in an R-squared score of 0.8838.

ElasticNet Regression: The ElasticNet model initially showed a low train score of 0.33 and a test score of 0.32. Hyperparameter tuning determined the best alpha value (0.05), improving the test score to 0.86. Model evaluation on the test data resulted in an R-squared score of 0.8574.

Model Comparison:

Based on R-squared score, Mean Absolute Error (MAE), Mean Squared Error (MSE) and Root Mean Squared Error (RMSE), Ridge regression outperforms Lasso and ElasticNet. Ridge achieved the highest R-squared score of 0.8838, indicating the best fit for the data.

Final Model:

The Ridge regression model is selected as the final model for House price prediction, with a test score of 0.8838. This model is expected to provide accurate predictions for house prices. The project successfully demonstrates the implementation of regression models for house price prediction, with Ridge regression as the best-performing model.
