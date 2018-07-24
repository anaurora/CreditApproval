# Credit Approval Prediction (Binary Classification)

This dataset is an excellent example of how to deal with sensitive/obscure data. Domain knowledge, while advantageous, is not a necessity and we will see how to develop a good predictive model with domain expertise!


This dataset is posted in this project's GitHub repository, while in this notebook I have ingested it through Google Drive. Feel free to replace the ingestion method with your own! Machine Learning algorithms used in this project are Logistic Regression, K-Nearest Neighbours, Linear Support Vector Classification and Random Forest classifier. 

## Dataset information:

**Credit_Scoring_Clean.csv**: This dataset contains several features that govern an individual's application for credit. We do not know when this dataset is from, and if this is for a credit card application, or a loan, or any other form of credit. In addition to this, many of the features have been converted to meaningless categorical variables or scaled numerical ones, to protect the data of the individual. The outcome is binary, where a *1* implies a successful application for credit and *0* implies an unsuccessful application. 

Also, as can be gleaned from the file name, the dataset does not require any clean up.

## Goals:

1. Perform feature selection to eliminate unnecessary variables or those that introduce bias.

2. Develop a predictive model to judge future credit applications.

3. Compare with other models to see if prediction can be improved.

## Results:

The clear winner is the Random Forest algorithm. Ensemble methods like the Random Forest classifier are a particulary excellent way of dealing with classification problems, even though they are significantly more computationally expensive. This is evidenced by an 84% accuracy rate for the Random Forest algorithm, compared to the second best Logistic Regression, with an accuracy rate of 75%!
