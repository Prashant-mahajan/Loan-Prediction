# Loan-Prediction

Feature analysis:

Chisquare test to find feature dependence for categorical variables <br>
Pearson correlation to find correlation between continuous variables <br>
One way anova to find correlation between continuous and categorical variables <br>
Data is having many missing values so missing values imputation was performed in following ways: <br>

For categorical variables <br>

1. Treat NAs as separate categories 
2. Replace by mode 
3. For continuous variables 
<br>
Replace by mean of feature <br>
Group average (Grouped by features found from one way ANOVA) <br>
Feature Transformation: <br> 

One hot encoding <br>
Normalization <br> 
2 way interactions <br>
Manually crafted features <br>
Models: <br>

Logistic Regression (Best model) <br>
Random forest <br> 
Extra trees <br> 
Gradient boosting machine <br> 
Naive Bayes <br> 
K-nearest neighbours <br>
Ensemble Stacking <br>

Competition Link: https://datahack.analyticsvidhya.com/contest/practice-problem-loan-prediction-iii/

