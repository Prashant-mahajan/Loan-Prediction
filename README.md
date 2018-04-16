# Loan-Prediction

Competition Link: https://datahack.analyticsvidhya.com/contest/practice-problem-loan-prediction-iii/

Feature analysis:

Chisquare test to find feature dependence for categorical variables
Pearson correlation to find correlation between continuous variables
One way anova to find correlation between continuous and categorical variables
Data is having many missing values so missing values imputation was performed in following ways:

For categorical variables

Treat NAs as separate categories
Replace by mode
For continuous variables

Replace by mean of feature
Group average (Grouped by features found from one way ANOVA)
Feature Transformation:

One hot encoding
Normalization
2 way interactions
Manually crafted features
Models:

Logistic Regression (Best model)
Random forest
Extra trees
Gradient boosting machine
Naive Bayes
K-nearest neighbours
Ensemble Stacking