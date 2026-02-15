# SecureTrust Bank – Intelligent Loan Approval System

## Project Overview

SecureTrust Bank processes hundreds of personal and home loan applications daily across urban and rural regions of India. Traditionally, loan approvals were handled through a manual verification process where loan officers reviewed income proofs, employment details, credit history, and other financial documents.

This manual system resulted in:

- Rejection of good customers, leading to loss of business

- Approval of high-risk customers, leading to financial losses

- Bias and inconsistency in decisions

- Slow processing time

To solve these issues, this project develops a Machine Learning-based Intelligent Loan Approval System that predicts whether a loan should be Approved (1) or Rejected (0) before final human verification.

## Objective

Build a Machine Learning classification model that:

- Learns hidden patterns from historical loan data

- Predicts loan approval status accurately

- Reduces financial risk

- Ensures faster and unbiased decision-making

- Assists loan officers in final verification

## Dataset Description

Dataset Description

Each row represents one loan applicant.

## Target Variable

Loan_Approved
1 = Approved
0 = Rejected

## Feature Columns

- Applicant_ID – Unique applicant ID
- Applicant_Income – Monthly income of applicant
- Coapplicant_Income – Monthly income of co-applicant
- Employment_Status – Salaried / Self-Employed / Business
- Age – Applicant age
- Marital_Status – Married / Single
- Dependents – Number of dependents
- Credit_Score – Credit bureau score
- Existing_Loans – Number of already running loans
- DTI_Ratio – Debt-to-Income ratio
- Savings – Savings balance
- Collateral_Value – Value of collateral provided
- Loan_Amount – Loan amount requested
- Loan_Term – Loan duration (months)
- Loan_Purpose – Home / Education / Personal / Business
- Property_Area – Urban / Semi-Urban / Rural
- Education_Level – Graduate / Postgraduate / Undergraduate
- Gender – Male / Female
- Employer_Category – Govt / Private / Self

## Tech Stack

**Programming Language** - Python

Libraries Used ->

**Pandas and NumPy** for data processing <br><br>
**Matplotlib and Seaborn** for visualization <br><br>
**Scikit-learn** for model building

## Project Workflow

1. **Data Collection**
Historical loan applicant dataset

2. **Data Preprocessing**
- Handling missing values
- Encoding categorical variables
- Feature scaling where required


3. **Exploratory Data Analysis**
- Distribution analysis
- Correlation analysis
- Approval rate comparisons

4. **Model Building**

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Naive Bayes

5. **Model Evaluation**

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Expected Outcome

The final model should:

- Minimize false approvals to reduce financial loss

- Minimize false rejections to retain good customers

- Provide consistent and unbiased decisions

- Reduce loan processing time significantly

## Model Performance Results

<img width="497" height="780" alt="image" src="https://github.com/user-attachments/assets/cdfc958d-db8b-4d80-b5b7-632b4f71ae25" />
]

## Final Model Selection

Logistic Regression achieved the highest accuracy (87.5%) and balanced precision-recall performance, making it the selected model for deployment.

## Business Impact

- Increased customer satisfaction
- Reduced financial risk
- Faster loan approval process
- Data-driven decision-making

## Author

Vaibhav Batta <br>
Machine Learning Engineer
