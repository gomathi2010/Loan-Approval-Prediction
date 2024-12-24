# Loan-Approval-Prediction

The dataset contains 13 features : 

1	Loan - A unique id 

2	Gender - Gender of the applicant Male/female

3	Married	- Marital Status of the applicant, values will be Yes/ No

4	Dependents - It tells whether the applicant has any dependents or not.

5	Education	- It will tell us whether the applicant is Graduated or not.

6	Self_Employed -	This defines that the applicant is self-employed i.e. Yes/ No

7	Applicant Income -	Applicant income

8	Coapplicant Income	- Co-applicant income

9	Loan Amount	- Loan amount (in thousands)

10	Loan_Amount_Term -	Terms of loan (in months)

11	Credit_History -	Credit history of individual’s repayment of their debts

12	Property_Area -	Area of property i.e. Rural/Urban/Semi-urban 

13	Loan_Status -	Status of Loan Approved or not i.e. Y- Yes, N-N


**Importing Libraries and Dataset**

To begin, we need to import the following libraries:

- **Pandas**: Used to load and manipulate the DataFrame.
- **Matplotlib**: Employed for visualizing data features, such as creating bar plots.
- **Seaborn**: Utilized to visualize correlations between features through a heatmap.

**Data Preprocessing and Visualization**

Retrieve the number of columns with an object data type. 

Then, visualize the unique values in these columns using a bar plot to identify which values are most dominant in the dataset.

The heatmap illustrates the correlation between Loan Amount and Applicant Income, highlighting the relationship between these two variables. It also reveals that Credit History has a significant impact on Loan Status.

**Splitting Dataset**

Split the dataset into features (X) and target variable (y), then use train_test_split to divide the data into training and testing sets.

**Model Training and Evaluation**


Since this is a classification problem, we will use the following models:

K-Nearest Neighbors Classifier (KNeighborsClassifier)

Random Forest Classifier (RandomForestClassifier)

Support Vector Classifier (SVC)

Logistic Regression (LogisticRegression)

**Conclusion**

Predicted loan approval outcomes with 82% accuracy on the testing dataset by deploying a Random Forest Classifier, optimizing the model through feature selection and hyperparameter tuning to enhance prediction reliability.
