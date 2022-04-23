# Welcome to Sparkify Churn Data

## About

This is a Mini-Project for CS1015 (Introduction to Data Science and Artificial Intelligence) which focuses on Sparkify from [Udacity](http://udacity-dsnd.s3.amazonaws.com/sparkify/mini_sparkify_event_data.json). 
  
## Contributors

- @AloysiusTan - Code (Data Visualization, Data Extraction, Feature Engineering, Modelling, Value Proposition)
- @Yu En - Data Visualization, Data Extraction and Slides
- @Andy - Data Visualization, Data Extraction and Slides

## Problem Definition

- Are we able to predict if a paid user will churn based on the user's activity on the platform?
- Which model would be the best to predict it?

## Models Used

1. Logistic Regression
2. Random Forest Classification

## Conclusion

- Clustering allows us to understand the different behaviours of different segments of users which can help to target product intervention.
- Upsampling imbalanced data improved model performance especially on the minority class
- Logistic Regression did not perform well with non-linearly correlated variables
- Yes, it is possible to predict if a user will churn with acceptable amount of accuracy and recall

## What did we learn from this project?

- Handling imbalanced datasets using upsampling methods
- Logistic Regression and Random Forest Classification from sklearn
- Usage of clustering techniques (K-Means and DBSCAN)
- Feature Importance with Random Forest
- Collaborating using GitHub
- Evaluations of Classification Models using Precision, Recall and ROC curve
- Identifying behavioural time trends
- Hyperparameter tuning using GridSearchCV
