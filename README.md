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
- @sanjsky24
- @mahipandcy

## Problem Definition 
- Identification and quantification of the most influential factors contributing to the risk of a heart attack.
- Verification of whether both models employ identical variables for the assessment of heart attack risk through machine learning models.

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
- The actual comparision of two models using the ROC curve
- the usage of packages like Radnom Forest classifier and Gradient Boosting existing in anaconda jupyter.
- The implemntation of google collab.

## Conclusions
- 

## References
- https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset/data
- https://www.heavy.ai/technical-glossary/feature-selection#:~:text=Feature%20selection%20is%20the%20process,of%20datasets%20continue%20to%20grow. 
- https://www.datacamp.com/tutorial/random-forests-classifier-python
- https://www.datacamp.com/tutorial/guide-to-the-gradient-boosting-algorithm
- https://developers.google.com/machine-learning/crash-course/classification/roc-and-auc#:~:text=An%20ROC%20curve%20(receiver%20operating,False%20Positive%20Rate
- https://www.analyticsvidhya.com/blog/2020/06/auc-roc-curve-machine-learning/
- https://scikit-learn.org/stable/modules/feature_selection.html


