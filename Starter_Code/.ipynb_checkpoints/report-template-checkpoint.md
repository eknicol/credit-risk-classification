# Module 12 Report Template

## Overview of the Analysis
An analysis was performed on lending data to establish whether it is possible to predict a healthy vs. high-risk loan based on variables. 
These variables included the size of the loan, the interest rate, borrower income and debt-to-income ratio.

To achieve this a Pandas dataframe was created that allowed the data to be split into test and training data.
A LogisticRegression model was then on the training data. A prediction was then created using the testing data.

## Results
A classification report and confusion matrix were created to provide some results and establish how effective the prediction model was. 

* LogisticRegression model:
   * Accuracy: 99%
   * Precision: Class 0 - 100%, Class 1 - 87%
   * Recall: Class 0 - 100%, Class 1 - 89%
   * F1: Class 0 - 1.00, Class 1 - 0.88

## Summary
The model shows high precision for Class 0 with 100%, with lower rate of precision for Class 1 with 89%. 
Overall accuracy was 99%.

I wouldn't recommend this model as it is more important to accuractely predict Class 1, which is the high risk loan category. 
The accuracy should be above 89%, ideally 99%.
