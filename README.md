# SC1015 DSAI Mini-Project: Heart attack risk analysis and prediction

![CLICK HERE (1)](https://github.com/sanjsky24/DSAI-mini-project/assets/157721052/ca790e44-ee2e-4032-af40-061727ae130b)


## About 
This is a Mini-Project for SC1015(Introduction to Data Science and Artificial Intelligence) which focuses on the crucial factors contributing to the risk of Heart Attack.
For detailed walkthrough please follow through the codes in the following order:

1. Data Extraction
2. Data exploration
3. Machine Learning
4. Final insights

## Contributors
- @sanjsky24 - Data Extraction, Data Exploration, Machine Learning, Final insights
- @mahipandcy - Data Extraction, Data Exploration, Machine Learning, Final insights

## Practical Motivation
In a world where over half the population is at risk of heart attack, with death records reaching a staggering 20.5 million as of 2021 , the need for effective strategies to tackle this health crisis is urgent.So in this world of heart attack prone population, we believe that the proper exploration, analysis and computing of the dataset will allow us to help domain experts in this case ,the physicians , to optimize treatment strategies as understanding the relationship between various factors. Understanding how various factors relate to the likelihood of a heart attack can guide tailored interventions. For instance, recognizing the impact of exercise-induced angina on heart attack risk can help customize treatment for individuals, ultimately leading to better cardiovascular health management and improved patient outcomes.
By performing: Data cleaning, exploratory analysis and used machine learning models to a complete analysis of our dataset, this can be considered as research which is done upon a small sample of data and the results can be implemented not only in the fields that we believe can bring a prominent change but to anybody who finds this useful.

## Problem Definition 
- Exploratory analysis of variables and Feature selection to statistically rank the features contributing to the risk of a heart attack. 
- Computing the accuracies of two machine learning models and comparing on the basis of 13,8 and 3 variables.
  
## Models Used
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting

## Our approach to the Dataset
- After the **extraction of our dataset** into our jupyter notebook, we performed cleaning and the checking of the null values
- Moving on to the exploratory data analysis, we have performed **EDA** to get to know the role of each categorical and numerical variables in order to give a detailed analysis of what we have understood from the dataset
- Separating it into numeric and categorical visualization allowed us to view our dataset form **two persepctives**.
- In order to properly understand and analyse the role of each variable with the target ' output' variable we have performed feature selection with the help of **logistic regression** in order to analyse the variables from a approach we have never been taught.
- We have chosen to perform **feature selection** as it gives us the most consistent and non redundant features(variables) for the construction of our models.
- **Based** on the feature selection through logoistic regression we have utiised two models Random Forest Classifier and Gradient Boosting.
- Through our models we were able to actually perform the methods on 13 variables, 8 variables and then 3 variables.
- We compared the accuracies of the two models using ROC curves and confusion matrices.
- In the end we have shared our insights on the accuracies of the models which implements are learning.

## What did we learn from this project ?
- The factors which contribute to the risk of heart attack the most.
- Collaboration on GitHub
- Machine learning mdoels of Logistic regression,Random Forest Classifier and Gradient Boosting.
- The importance of feature selection in selecting the most important features
- The actual comparision of two models using the **ROC curve.**
- the usage of packages like Radnom Forest classifier and Gradient Boosting existing in anaconda jupyter.
- The implemntation of google collab.
- The concepts about precision, recall and F1score

## Conclusions
- From the correlation analysis, we have realsied that the factors with the highest correlation are the "thalachh" and the "exng" variables.
- Specifically from the numeric correlation,"thalachh" came out to have the highest correlation and from the categorical visualization "exng" came out to have the highest correlation
- From Feature selection, **"Sex (sex)"** and **"Thallium Stress Test Result (thall)"** appear to be the most important features.
- On comparing the accuracies through the ROC curve, we found out that the more the number of variables the more accurate the model was in the case of random forest, but suprisingly Gradient Boosting did not follow the same trend.
- Ulitmately, the accuracy of the Random Forest model for all variables is 0.86 or 86% and the accuracuy for the Gradient Boosting model for all the variables is 0.85 or 85%

## References
- https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset/data
- https://www.heavy.ai/technical-glossary/feature-selection#:~:text=Feature%20selection%20is%20the%20process,of%20datasets%20continue%20to%20grow. 
- https://www.datacamp.com/tutorial/random-forests-classifier-python
- https://www.datacamp.com/tutorial/guide-to-the-gradient-boosting-algorithm
- https://developers.google.com/machine-learning/crash-course/classification/roc-and-auc#:~:text=An%20ROC%20curve%20(receiver%20operating,False%20Positive%20Rate
- https://www.analyticsvidhya.com/blog/2020/06/auc-roc-curve-machine-learning/
- https://scikit-learn.org/stable/modules/feature_selection.html


