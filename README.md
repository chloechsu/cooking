# Cuisine Classification based on Recipe Ingredients

From the Kaggle competition [What's Cooking](https://www.kaggle.com/c/whats-cooking) in 2015. 

## Table of Contents
* Preprocessing
* Idea 1: Bag of Words + Logistic Regression
* Feature Selection
  + Variance Threshold (unhelpful)
  + Mutual Information (unhelpful)
  + Chi2 (unhelpful)
  + Lasso Logistic Regression (helpful)
* Analyze the Weakness of Bag of Words + Logistic Regression
* Idea 2: Random Forest with Bag of Words and Logistic Regression Results as Features
* Idea 3: Random Forest for Confused Cuisine Pairs
  + French vs Italian
  + Modify Logistic Regression Predictions with French vs Italian Classifier
  + Random Forest for each Confused Cuisine Pair
  
### Test Scores (Accuracy)
* Bag of Words + Random Forest: 0.679
* Idea 1 Bag of Words + Logistic Regression: 0.777
* Idea 2: 0.789
* Idea 3: 0.782
