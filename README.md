Project Description: Loan Prediction Analysis

Project Goal:
Predict whether a loan applicant will be approved (Loan_Status) based on their personal, financial, and property-related information.

Dataset Features:

Customer_ID : Unique customer identifier

Gender : Applicant's gender (Male/Female)

Married : Marital status

Dependents : Number of dependents

Education : Education level

Self_Employed : Self-employed status

Applicant_Income : Applicant's income

Coapplicant_Income : Coapplicant's income

Loan_Amount : Loan amount requested

Loan_Amount_Term : Loan repayment term

Credit_History : Credit history indicator

Property_Area : Property location

Loan_Status : Loan approval status (target variable)

Project Steps:

Exploratory Data Analysis (EDA):

Visualize data distributions using Pie Charts and Count Plots.

Analyze relationships between features and loan approval.

Data Preprocessing:

Convert categorical features to numerical using get_dummies.

Encode target variable Loan_Status (Y → 1, N → 0).

Scale numerical features if needed using MinMaxScaler or StandardScaler.

Model Building:

Train multiple classification models such as:

Decision Tree

Random Forest

Bagging

Logistic Regression

Fit models on training data and evaluate performance on test data.

Evaluation:

Measure performance using Accuracy, Precision, Recall, and F1-Score.

Plot Confusion Matrices to visualize prediction errors for each model.

Expected Outcomes:

Identify key factors affecting loan approval.

Compare model performance to select the best predictor.

Enable predictions for future loan approvals.
logistic is hightest accuracy is 82%
after smote
bagging is high accuracy is 84%
