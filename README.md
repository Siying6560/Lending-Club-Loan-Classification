# Lending-Club-Loan-Classification

**Data Reference**: Kaggle (https://www.kaggle.com/datasets/wordsforthewise/lending-club?resource=download) 

### Overview
LendingClub is a US peer-to-peer lending company, headquartered in San Francisco, California. It was the first peer-to-peer lender to register its offerings as securities with the Securities and Exchange Commission (SEC), and to offer loan trading on a secondary market. LendingClub is the world's largest peer-to-peer lending platform.

### Problem statement
Given historical data on loans given out with information on whether or not the borrower defaulted (charge-off), can we build a model that can predict whether or not a borrower will pay back their loan? This way in the future when we get a new potential customer we can assess whether or not they are likely to pay back the loan. 

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
    - 
    - 
    - 
    - removing outliers
    - normalizing data
5. Setting a baseline
6. Assessing multiple alogorithms
    - ALgorithm selected
    - Hyperparameter tuning
7. Performance of the selected model
8. Drawing conclusions - summary