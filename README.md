# MOD_20_challange

In this challange I made a machine learning model that I trained with predictions to make decisions on the risks of loans.
The fincial data was on loan size, interest rate, borrower debt, and number of loans. I used this data to train a machine learning model to predict if a loan is going to be a healthy loan or a high risk loan.

In the first model with the orginal data it predicited healthy loans 100% of the time whilst predicting high risk loans 88% of the time while this is still a good stat. If I were a compnay using these maqchine learning p-redictions I would of used the second model based of the resampled training data. In this model it predicted healthy laons at 95% and high risk loans at 94% this would make it easier to make and informed decison and would reduce your likelyhood of errors.


results
Machine learning model 1:
precision    recall  f1-score   support

           0       1.00      1.00      1.00     18759
           1       0.87      0.89      0.88       625

    accuracy                           0.99     19384
   macro avg       0.94      0.94      0.94     19384
weighted avg       0.99      0.99      0.99     19384


Machine learning model 2:
 precision    recall  f1-score   support

           0       0.90      0.99      0.95     56277
           1       0.99      0.89      0.94     56277

    accuracy                           0.94    112554
   macro avg       0.95      0.94      0.94    112554
weighted avg       0.95      0.94      0.94    112554
