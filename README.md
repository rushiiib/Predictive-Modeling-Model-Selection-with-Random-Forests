# Model Selection and Forecasting with Random Forests on 20,000 Observations

This project builds a predictive model for estimating the response variable Y using approximately 19 numeric predictors and 20,000 training observations. The dataset was split into 80% training and 20% validation, and all models were evaluated using 10-fold cross-validated RMSE and validation RMSE. After selecting the best model, the final Random Forest was refit on all training data and used to generate test predictions. All steps were reproduced in the accompanying .qmd file using a fixed random seed.



