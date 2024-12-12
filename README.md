# Module-20-Credit-Risk-Classification


# Credit Analysis 

• The results:   
•                 precision    recall  f1-score support 
                
• Class Purple:     
1.00       1.00     1.00     18759  
• Class Yellow:     
0.87       0.95     0.91      625   
                  
• accuracy:                             
                    0.99    19384  

• macro avg:         
0.94      0.97     0.95      19384 
    
• weighted avg:      
0.99      0.99     0.99      19384 

A summary: This challange required a machine learning model that can identify credit worthiness of borrowers. Historical data is from peer-to-peer lendingwas used  All four columns boast high scores. Using this credit analysis will have outstanding results. Regular maintainance is required for spectacular results.

# Split the Data into Training and Testing Sets
Open the starter code notebook and use it to complete the following steps:

Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.

note
A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.

Split the data into training and testing datasets by using train_test_split.

Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:

Fit a logistic regression model by using the training data (X_train and y_train).

Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

Evaluate the model’s performance by doing the following:

Generate a confusion matrix.

Print the classification report.

Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

