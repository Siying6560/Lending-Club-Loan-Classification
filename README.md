# Lending-Club-Loan-Classification

**Data Reference**: Kaggle (https://www.kaggle.com/datasets/wordsforthewise/lending-club?resource=download) 

### Overview
LendingClub is a US peer-to-peer lending company, headquartered in San Francisco, California. It was the first peer-to-peer lender to register its offerings as securities with the Securities and Exchange Commission (SEC), and to offer loan trading on a secondary market. LendingClub is the world's largest peer-to-peer lending platform.

### Problem statement
Given historical data on loans given out with information on whether or not the borrower defaulted (charge-off), can we build a model that can predict whether or not a borrower will pay back their loan? This way in the future when we get a new potential customer we can assess whether or not they are likely to pay back the loan. 

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.
If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA and machine learning is the aim of this project.

In addition, we can help company understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.

### Lending Club Loan feature directionary:** https://www.kaggle.com/datasets/jonchan2003/lending-club-data-dictionary
* loan_amnt - The listed amount of the loan applied by the borrower.
term - The number of payments on the loan, where values are in months and can be either 36 or 60.
* int_rate - The interest rate on the loan
* sub_grade - Assigned loan subgrade score based on borrower's credit history
* emp_length - Borrow's employment length in years.
* home_ownership - The homeownership status provided by the borrower (eg rent, own, mortgage, etc)
* annual_inc - The self-reported annual income provided by the borrower
* addr_state - The state provided by the borrower in the loan application
* dti - A ratio calculated using the borrower’s total monthly debt payments on the total debt obligations, excluding mortgage, divided by the borrower’s monthly income.
* revol_util - Revolving line utilization rate, or the amount of credit the borrower is using relative to all available revolving credit.

### Steps of the project
1. Data reading
2. Exploratory data analysis (Data visualization)
3. Data preprocessing
    - removing/consolidating repetitive/unnecessary features
    - removing/ filling missing values
    - converting categorical variables into dummy variables
    - removing outliers
    - normalizing data
(5. Setting a baseline)
6. Assessing multiple alogorithms
    - ALgorithm selected
    - Hyperparameter tuning
7. Performance of the selected model
8. Drawing conclusions - summary

### Takeaway:
- Deal with inbalanced data set: 
    * split train, testing data: add stratify = y
    * cross validation: RepeatedStratifiedKFold
- Boosting technique works well with inbalanced data set
- There is a tradeoff between performance and running time