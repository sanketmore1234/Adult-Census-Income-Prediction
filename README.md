# Adult-Census-Income-Prediction
Adult Census Income Prediction Machine Learning project
Data cleaning:
Handling null values - strip white spaces, impute nulls with mode, median

One hot encoding for categorical variables

Checked the significance of columns using stats models -cols greater than 0.05 were eliminated, 

Used gridsearch CV for hyper parameter tuning , 
pipeline of - standard scalar, polynomial features, 

k fold cross validation, used scoring parameter as f1 (since the false positives were more important)

Used weights as balanced since one class was very less than others

1. Used logistic regression with hyperparameter tuning
2. Used Ridge CLassifier with hyperparameter tuning
3. Used Lasso Classifier with hyperparameter tuning
4. Used Support Vector Classifier with hyperparameter tuning
5. Used Random Forest with hyperparameter tuning

Selected the best performing model keeping in mind F1 and Recall scores
