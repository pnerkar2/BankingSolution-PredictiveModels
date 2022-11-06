# BankingSolution-PredictiveModels
Use lasso and ridge regression models to predict if the client will subscribe a bank term deposit (variable y)

1. Estimate lasso models using appropriate features and parameters for the following dataset (with Y as the binary predictor, 0 or 1). 
2. Convert categorical variables (i.e., if class of that column == character/factor) to dummy variables before entering in lasso/ridge. 
3. Split the data into train (80%) and test (20%) using set seed 40. 
4. Calculate the accuracy from the model for train and test data. (accuracy around 91%) 
5. Try cross-validation (for 6,...9, 10 folds) using cv.glmnet within a loop for lasso and for ridge and print the accuracy for each of the 5 no. of folds i.e., 6...10. [1 pt ]



This dataset is publicly available for research. The bank-additional.csv has 10% of the examples (4119), randomly selected from bank-additional-full.csv.
The smallest dataset is provided to test more computationally demanding machine learning algorithms.

Citation: [Moro et al., 2014] S. Moro, P. Cortez and P. Rita. A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, In press, http://dx.doi.org/10.1016/j.dss.2014.03.001


