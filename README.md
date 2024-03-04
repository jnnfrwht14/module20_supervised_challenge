# module20_supervised_creditrisk

## Purpose of the analysis: 
* The financial information provided was a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.
* The goal was to predict loans with a high risk of defaulting.

  ### Machine learning was used:
* Fit a logistic regression model by using the training data (X_train and y_train).

* Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

* Evaluate the model’s performance by doing the following:
  * Generate a confusion matrix.
  * Print the classification report.
* I used LogisticRegression to predict defaulting the loans, using train_test_split.

## Results:

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Classification Report:
                            precision    recall  f1-score   support
            
                       0       1.00      1.00      1.00     56271
                       1       0.86      0.90      0.88      1881
            
                accuracy                           0.99     58152
               macro avg       0.93      0.95      0.94     58152
            weighted avg       0.99      0.99      0.99     58152

       
     * The recall for healthy loans is high. The recall for loans at risk is lower, which indicates a lower false negative rate. The accuracy appears to be very high, but there could be an imbalance since the number of healthy loans represents 96.6% of the model.
## Summary:

Since there are many variables that can lead to loan defaults, I would suggest another round of machine learning is completed - SVM, to ensure the data isn't imbalanced.
