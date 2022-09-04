# LOAN DATA EXPLORATION
## by Ashinze Emmanuel Chidi


## Dataset

> This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. The link to the data set is as follows https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv

## Summary of Findings

### Univariate Analysis

>1. Most of the loans are Current. Roughly 66% of all loans are current

>2. Almost all the Borrowers are gainfully employed

>3. Over 50% of the borrowers have less than 6 years work duration

>4. Professionals, Salesmen ,Executives and programmers borrow more than the other professions. Judges and dentists have the lowest number of borrowers.

>5. Few of the borrowes have 10.0 and above and few have below 3.0 Prosper score. This is expected as loans will not given to an unsuccessful individual and highly successful individuals might not need loans

>6. The Borrower Rate seems to be normally distributed with a huge spike at 0.32. It seems that a lot of the loans have a rate of 0.32 

>7. 30%  of the borrowers earn from 50,000 - 74,999 and only a few unemployed borrowers.

>8. Most of the loans are 36 months in duration with just  few 12 months loan.

>9. Most of the loans are used for Debt Consolidation and Health Improvement.

>10. California, New York and Texas have the highest amount of borrowers.


### Bivariate Analysis

>1. The borrowers with current loans dominates across the prosper scores. The loans with final payment are relatively scarce

>2. Most Borrowers prefer the 36 months loan term regardless of the income range.

>3. There seems to be a  very weak positive relationship between the Employment Duration and Loan Original Amount.  Maybe the time spent at work does not influence amount of loans.

>4. Across most of the loans, Employed borrowers dominate the numbers. This is highly expected
 

### Multivariate Analysis

>1. Most loans with high loan amount are for a long term and this trend is constant across the different loan statuses.

>2. Loaners who are about to pay off their loan with a short term have a high monthly income.

>3. There is no loaner with zero monthly income. Most loaners had a short term loan

## Key Insights for Presentation

> The status of a loan is a huge insight if patterns can be drawn with other features in the dataset. The loan status depends on the income and expenses of a person or company. Therefore EmploymentStatus, IncomeRange, EmploymentStatusDuration, Borrower Rate will help in predicting the status of the loan. Analysis was done on the dataset to discover what affects the status of a loan.