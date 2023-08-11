# ChatGPT Classification Blueprint (Prompts)

## ML Pipeline
1. Import Packages
2. Import Data (train, test, sample_submission)
3. Check Data
4. Check Target Feature
5. Partition Data into y and X (train, test)
6. Extract numerical and categorical feature names
7. Validation Strategy – train test split
8. Pre-processing framework (Basic)
9. Build Model and Make Predictions
10. Make and Export Submission File


### 1/ Import Packages
> Write a code to only import various packages to build a classification model.
Using train and test data from Kaggle.
Also, we will use train test split.
And we will use the classification report for performance.

### 2/ Import Data (train, test, sample_submission)
> Read both train, test and sample_submission from this location ‘input’ folder.
Into DataFrames called train, test and submission.
Use pandas.


### 3/ Check Data
>How to check data?
Why to check data?
Provide information in bullet points.
Write code to check data.


### 4/ Check Target Feature
>Why check the target column? How to check the target column?
Check the “target” column for class imbalance .
Here are the columns names in the dataset names “train”.


### 5&6/ Partition Data 
>Write a code to partition “train”, “test” data 
train into y, X
test into X_test
Use X, y to split into – X_train, X_val, y_train, y_val
Exclude “target” and “enrollee_id” from X data

### 7/ Extract numerical and categorical feature names
>Write a code to extract numerical & categorical column names from X_train.
Using dtypes.
Then print the list of column names.


### 8/ Validation Strategy – train test split
>Write a code to perform the following:
Missing Value Treatment for Numerical features using median.
Use the numerical list - numerical_columns.
Write in the following method.
1 - Import Package.
2 - Create an Instance.
3 - Fit Instance – X_train.
4 - Transform – X_train, X_val, X_test.


### 9/ Build Model and Make Predictions
>Write a code to build Logistic Regression Model.
Make predictions on X_train, X_val, X_test.
Calculate the Classification report for X_train and X_val.


### 10/ Make and Export Submission File
>Write a code to create a dataframe called “submission” with 2 columns “enrollee_id” and “target”.
Get “enrollee_id” from test.
Get “target” from a dataframe with one column “y_test_pred”.
Export the same in output folder – ‘output/submission.csv’.

