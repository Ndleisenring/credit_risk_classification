# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
   * Model 1 was trained on the original data given to us. This model had a 94.4% accuracy predicting two labels. This model is very good at predicting the healthy loans, with both precision and recall scores of 100%. However, the model's performance in predicting the high-risk loans can be improved. A precision score of 87% and a re-call score of 89% leave some room for improvement, incorrectly identifying a high-risk loan as any other can be dangerous for a lender.
  
* Machine Learning Model 2:
  * Model 2 was trained on the resampled data and had an accuracy of 99.6% in predicting the two labels.Once again this model had a 100% score predicting healthy loans.The precision score for high-risk loans on this model was also 87% but the re-call was 100%. Definitely an improvement as the overall model accuracy was 99.6%.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* I would recommend the second model if I was a money lender, the 99.6% accuracy score is fairly strong.This model predicted all of the high-risk ones correctly which is where a lender could go under.Unfortunately a few of the healthy loans were misidentified as high-risk but for the business' sake it's better to be safer than sorry.
