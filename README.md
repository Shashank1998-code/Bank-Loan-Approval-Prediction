# Bank-Loan-Approval-Prediction
Supervised Linear Classification Model to Predict Bank Loan Approval using Logistic Regression

This is a classification problem in which we need to classify whether the loan will be approved or not. 
Classification refers to a predictive modeling problem where a class label is predicted for a given example of input data. 

Problem-----
A Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. 
These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. 
To automate this process, they have given a problem to identify the customers segments, 
those are eligible for loan amount so that they can specifically target these customers. Here they have provided a partial data set.

Link : https://www.kaggle.com/datasets/ninzaami/loan-predication

Categorical Columns: Gender (Male/Female), Married (Yes/No), Number of dependents (Possible values:0,1,2,3+), Education (Graduate / Not Graduate), 
Self-Employed (No/Yes), credit history(Yes/No), Property Area (Rural/Semi-Urban/Urban) and Loan Status (Y/N)(i. e. Target variable)

Numerical Columns: Loan ID, Applicant Income, Co-applicant Income, Loan Amount, and Loan amount term

Conclusion
The Logistic Regression Model produced an Accuracy of 73%.
Hyper Parameter Optimization was carried out using Randomized Cross Validation and a new accuracy of 80.16% was obtained.

Feature engineering helped me increase my accuracy.
