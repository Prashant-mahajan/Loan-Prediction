# Loan-Prediction

## Feature analysis:

1. Chisquare test to find feature dependence for categorical variables <br>
2. Pearson correlation to find correlation between continuous variables <br>
3. One way anova to find correlation between continuous and categorical variables <br>
4. Data is having many missing values so missing values imputation was performed in following ways: <br>

### For categorical variables

1. Treat NAs as separate categories 
2. Replace by mode 

### For continuous variables 
1. Replace by mean of feature 
2. Group average (Grouped by features found from one way ANOVA) 

## Feature Transformation: 

1. One hot encoding 
2. Normalization  
3. 2 way interactions 
4. Manually crafted features 

## Models: 

1. Logistic Regression (Best model) 
2. Random forest 
3. Extra trees  
4. Gradient boosting machine 
5. Naive Bayes 
6. K-nearest neighbours 
7. Ensemble Stacking 

Competition Link: https://datahack.analyticsvidhya.com/contest/practice-problem-loan-prediction-iii/

