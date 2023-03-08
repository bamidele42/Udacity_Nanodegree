# Loan Data from Prosper, Data Exploration
 
 
## Dataset

The dataset contains 113,937 loans with 81 variables on each loan including 'LoanStatus', 'BorrowerState', 'Occupation', 'EmploymentStatus', and 'IncomeRange' among others.
For the purpose of the project only 16 variables were explored which include:
"ListingKey", "ListingNumber", "Term", "LoanStatus", "BorrowerAPR", "BorrowerRate", "LenderYield", "ListingCategory (numeric)", "BorrowerState", "Occupation", "EmploymentStatus", "IsBorrowerHomeowner", "IncomeRange", "IncomeVerifiable", "StatedMonthlyIncome","Investors"


## Summary of Findings

Borrowers that still in current category of loan status has majority count in the dataset while these borrowers also fall in the debt consolidation category while collecting loan. 

The dataset has most of the borrowers employed, most of the borrower tends to apply for loans with 36 months term period. The loans that have 12 month term has little activities, these shows that less borrowers actually apply to get this loan, Loans with 36 month term do not have too many activities either but borrowers still patronized more than 12 month term. I also observe that the LenderYield increases with Borrowerate in dataset.

There is a general linear trend in the relationship between the quantative fields in the dataset. I o bserve that there are borrowers that have completed loan payment across the dataset, one interesting trend is that current borrowers interest rate tend to start around 12% up 40%, there was no interest rate beyond this point.

I also find out that there are high number of borrowers that were charged off between 20 to 35% of lenderyield and  25 to 39 % borrowers interest rate. This means that there is higher chances of a borrower been charged off when the interest rate is high.



## Key Insights for Presentation

For the presentation, I focus on effects of key variables from the dataset on Loan status which the main variable used in this project. I started by briefly introducing the Loan Status variable, I followed it up by showing the relationships that key variables have with the loan status variable. As follows:
- Distribution of Term(mnoth) by loanstatus shows that borrowers generally prefer the 12 month loan duration than others
- Distribution of BorrowerAPR and LenderYield by Loan status revealed that there is higher chances that a borrower will charged off between certain percentage of interest rate.
- Distribution of Loan status and LenderYield by Ishomeowner shows that most the distribution of borrowers that own homes are lower compare those that do not own a home.
