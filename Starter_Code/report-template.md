# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.

The purpose of this analysis was to evalute the accuracy of a machine learning model that can predict the efficacy of potential borrows credit worthyness from lenders. 

* Explain what financial information the data was on, and what you needed to predict.

The dataset contains financial information on loan applications, loan sizes, intrest rates, borrow income, debt-to-income ratio, number of finance accounts, and total debts.

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).

The variables we used were healthy loans (0) and high risk loans (1). These were based on risk factors associated with the potential borrowers.

* Describe the stages of the machine learning process you went through as part of this analysis.

The stages of the learning process was preprocessing, training, and evaluation. Preproccessing consisted of a csv used as the dataset. This was loaded, then the target variables and features were seperated. Traiing consisted of training the model. The evaulautaion used confusion matrices, classification reports, and accuracy scores to determine the success rate. 

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

A logistic regression model was used to predict the likelyhood of loan classification, 0 or 1.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

                  precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.94      0.89       619

    accuracy                           0.99     19384
   macro avg       0.92      0.97      0.94     19384
weighted avg       0.99      0.99      0.99     19384

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?

The logistic model worked great for both accuracy and precision testing.

* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

It is more important to predict high risk loans as they are the most likely to default. However it does not seem to make a meaningfull difference with this dataset to performance on either end.


If you do not recommend any of the models, please justify your reasoning.


I would reccomend this model