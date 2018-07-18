# Loan-Prediction

## Feature analysis:

1. Chisquare test to find feature dependence for categorical variables <br>
2. Pearson correlation to find correlation between continuous variables <br>
3. One way anova to find correlation between continuous and categorical variables <br>
4. Data is having many missing values so missing values imputation was performed in following ways: <br>

### For categorical variables <br>

1. Treat NAs as separate categories 
2. Replace by mode 

### For continuous variables 
<br>
1. Replace by mean of feature <br>
2. Group average (Grouped by features found from one way ANOVA) 
<br>

## Feature Transformation: <br> 

1. One hot encoding <br>
2. Normalization <br> 
3. 2 way interactions <br>
4. Manually crafted features <br>

## Models: <br>

1. Logistic Regression (Best model) <br>
2. Random forest <br> 
3. Extra trees <br> 
4. Gradient boosting machine <br> 
5. Naive Bayes <br> 
6. K-nearest neighbours <br>
7. Ensemble Stacking <br>

Competition Link: https://datahack.analyticsvidhya.com/contest/practice-problem-loan-prediction-iii/

