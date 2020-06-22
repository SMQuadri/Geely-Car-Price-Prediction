# Geely-Car-Price-Prediction

This data science contest was hosted on kaggle by a chinese automobile company GEELY. Geely Auto aspired to enter the US market by setting up their manufacturing unit there and to produce cars locally. The goal was to model the price of cars with the available independent variables & to determine the correlation between different variables. By utilizing this I drew to a conclusion of which variables are the most correlated to the price of the car. Lastly, I was required to predict the price of cars in the test data provided by them.

Steps involved in this project :
1) Imported the required libraries and the dataset.
2) Analyzed the dataset.
3) Executed data cleaning operations.
4) Converted the categorical variables into numeric variables.
5) Implemented data visualization by plotting heatmap to find out the correlation between differenr variables and the target variable.
6) Performed data preprocessing.
7) train_test_split to divide the dataset into train and test sets.
8) Scaled the data using StandardScaler().
9) Performed feature selection using Recursive Feature Elimination (RFE).
10) Built the model using Ordinary Least Squares (OLS) to estimate the unknown parameters in to reduce the mean squared error of the linear regression model.
11) Checked the obtained summary of the OLS model using Variance Inflation Factor (VIF) to determine the presence of multicollinearity.
12) Selected the required features from the obtained VIF table and dropped the ones not required.
13) Continued this process till no unnecessary features are present for model evaluation and prediction.
14) Lastly, performed model prediction and evaluated the accuracy score of its performance.


## Note:
A humble request to the people who came here in search of code for this project, please don't copy the whole code and content. You have spent some time learning this subject. So, better try to write your code in your own way. It will further enhance your skills. If stucked somewhere, this repository is always here to help you.

## Happy Learning !!!
