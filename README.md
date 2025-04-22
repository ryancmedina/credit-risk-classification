# credit-risk-classification

The purpose of the analysis is to predict whether a loan is in good condition or at risk of defaulting.
The information we have on each loan are aspects such as loan size, interest rate, and total debt. 
We are trying to predict the "loan_status" attribute.
We split the data into training and testing data with train_test_split(). Then, we initialized a LogisticRegression model and fit it with the training data. Lastly, we predicted the testing data and displayed.

    - The accuracy is near perfect at a .99.
    - The precision of the '0' value is at a perfect 1.00, while the precision of the '1' value is at a considerably lower .85
    - The recall of both '0' and '1' values are great, at a .99 and .95 for each respectively

While the precision of the '1' value is a slight point of concern, I still highly recommend this model due to its high accuracy and recall.