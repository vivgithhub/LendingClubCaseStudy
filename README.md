# Case Study — Loan Exploratory Data Analysis   

**EDA to understand how consumer attributes and loan attributes influence the tendency of default.**

## Problem Statement  
  
A consumer finance company which specializes in lending various types of loans to customers, likes to make a decision for loan approval based on the applicant’s profile.  

Two types of risks are associated with the bank’s decision:
- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
- If the applicant is not likely to repay the loan,then approving the loan may lead to a financial loss for the company  

The data set contains the information about past loan applicants and whether they ‘defaulted’ or not.  
The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying  
the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

In this case study, we have used EDA to understand how consumer attributes and loan attributes influence the tendency of default.
When a person applies for a loan, there are two types of decisions that could be taken by the company:    
1. Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:  
- Fully paid: Applicant has fully paid the loan (the principal and the interest rate)   
- Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
- Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan
2. Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). 
Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)


## Scope  

``` 
* As a Data Scientist, help Lending Club(A marketplace for personal loans) to understand the driving factors behind loan defaulters and risky applications. 
* Lending Club can utilize this knowledge for its portfolio, risk assessment, acquire more customers and to maximize its revenue.
```

## Objective

``` 
* Leverage various Data Science techniques, models and algorithms of Exploratory Data Analysis(EDA) and discover patterns, spot anomalies, 
  risky loan applications and derive inferences/ insights from the data shared
* Translate the inferences into prescriptive recommendations that can be utilized by Lending Club to reduce the credit loss .

```
## Steps Followed in EDA

#### Step 1: Data Cleaning 
#### Step 2: Univariate Analysis
#### Step 3: Segemented Univariate Analysis
#### Step 4: Bivariate/Multivariate Analysis
#### Step 5: Results   


### Contributors

- Muniaraja Murugan(Group Facilitator)
- Vivek Trivedi(Team Member)


## Recommendations

- Applicants who are Self-Employed and less than 1 year of experience are more probable of Likely to be Defaulter
- Applicants with loan purpose ‘Repair’ is having higher number of unsuccessful payments on time.
- Loan for small business has the highest probability of Likely to be as a Defaulter of 26%. So, bank should take extra caution while approving the loan for purpose of 'small business'.
- Applicants with loan purpose as “credit card payment” or “debt consolidation” can be considered as high-risk applicants.
- Increase in Loan Amount is increasing the probability that person will default (increasing with highest at 25000 & above bracket)
- Increase in interest rate is increasing the probability that person will default (increasing with highest at 15% & above bracket)
- Low-income rage – People in the lower income bucket are more defaulters


##### This EDA assignment was done as part of "MS(Master of Science)" in Machine Learning and AI - IIIT,Bangalore & Liverpool John Moores University.
