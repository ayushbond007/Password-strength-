# Password-strength-
predicting the strength of the password 
we are predicting the strength of a user password 
for this matter we use  TF-iDF for the same and applied
logistic regression




     password   precision    recall  f1-score   support

           0       0.58      0.30      0.40     17866
           1       0.84      0.94      0.89     99313
           2       0.82      0.68      0.75     16749
    accuracy                           0.82    133928
    
    
    
   macro avg       0.75      0.64      0.68    133928
   
   
   
   
   
weighted avg       0.80      0.82      0.80    133928






hmm!!!!!!!!!!!!!!!!!!!

precision and recall of strength 1 is very high
because our data is biased towards 1 means lot of oassword have strength have level one
so to over come the baised data 
we can use the approach of STRATIFIED SMAPLING to over come the baisedness of data
