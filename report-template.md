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
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  * The logistic regression model had a high level of accuracy in predicting both healthy loan '0' and high-risk loan '1' labels. 
  * The precision for healthy loans is 1.00 (100%).  The recall for healty loans is 0.00 (99%) which indicates that 99% of actual healthy loans were corrected predicted.  
  * The precision for high-risk loans is also highly accurate with 0.85 (85%) correctly predicting loans that are actually high-risk.  The recall for high-risk loans is 0.91 (91%).  
  * The logistic regression model offers an high overall performance i.e. correctly predicting health and high-risk loans.


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  * The logistic regression model fit with oversampled data performs well in predicting both the '0' and '1' labels. 
  * The precision of 1.00 and recall of 0.99 scores for healthy loans shows that the oversampled data provided similar high accuracy.  
  * With precision of 0.84 and recall of 0.99 for high-risk also shows oversampling provied high overall accuracy.  
  * The recall is slighly lower in the oversampled data, which may indicate that oversampling may slightly degrade prediction accuracy. 
  * The geometric mean and information balance accuracy also show indicate high performance.  
  * Overall, oversampling data for logistric regression modeling still provides high accuracy in prediction loan risk.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
  * Machine Learning Model 1 with the original data seems to perform better than Machine Learning Model 2 with oversampled data.
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )  
  * The recall is slighly lower in the oversampled data for `1`'s, which may indicate that oversampling may slightly degrade prediction accuracy.

If you do not recommend any of the models, please justify your reasoning.
* Both Machine Learning models provided high accuracy levels. 