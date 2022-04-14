# Adult-Census-Income-Prediction
Adult Census Income Prediction Machine Learning project

# Libraries Used
1. Pandas
2. Scikit Learn
3. Statsmodels
4. Numpy

# Algorithms Used
1. Logistic Regression
2. Ridge Classifier
3. Lasso Classifier
4. Support Vector Classifier
5. Random Forest Classifier

# Data cleaning
Handling null values - strip white spaces, impute nulls with mode, median according to distribution

# Data Transformation
One hot encoding for categorical variables

# Feature reduction
Checked the significance of columns using stats models -cols greater than 0.05 were eliminated
Additionally, regularization will reduce the dimensions

# Hyper Parameter Tuning
Used gridsearch CV for hyper parameter tuning , 
pipeline of - standard scalar, polynomial features, 

# Cross Validation
k fold cross validation, used scoring parameter as f1 (since the false positives were more important)

Used weights as balanced since one class was very less than others

# Performance Criteria
Selected the best performing model keeping in mind F1 and Recall scores

Best Model paramters and performance is as follows
https://github.com/sanketmore1234/Adult-Census-Income-Prediction/blob/main/Best%20Model%20performance-%20Ridge.jpg


# Feature importances
The feature importances were plotted by using the model coefficients and showcasing the most influential parameters
