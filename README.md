# Understanding Why Borrowers Default : Analysis of Prosper Loan Data.
## by Olatunji Olarewaju


## Dataset

The data has the status of each of the 113,937 loans including, information such as the amount borrowed, the date, and some borrower's features such as income ranges and employment status. The data covered a period of 10 years, between 2005-2014.

## Summary of Findings

From the pairwise correlation plots of some selected features in the dataset, available bank card credit, interest rates, income ranges, employment status, credit score and home ownership were found to have some strength of relationship. In particular, credit score and bank card credit were found to be correlated with interest rates. But also, the bearing influence of interest rate on repayment outcome required investigation of the combined relationships of interest rates with other variables to unravel why borrowers default. 
In the multivariate investigation, the nature of the interplay of credit score and bank card credit in determining interest rates became clearer. 
Initially, interest rates was thought to be the reason for default on loans, but as investigation revealed, credit score and bank card credit were the determining factors leading to default.  Generally,  borrowers are likely to default if their score is 640 or less and have 50000 dollars or less as available bank card credit.I suspect that the high interest rate is a reflection of high investment risk that these category of borrowers represent,  but not the reason for their default on repayment.


## Key Insights for Presentation

- Payments are still ongoing for most of the loans, but no less than 10% of the borrowers have completely ceased loan repayment.
- Most borrowers took loans for the purpose of debt consolidation. 
- Loans were charged between 0 to 40% interest rates
- Interest rate showed negative correlation with credit score and bank card credit available. 
- For most borrowers who defaulted, or are chargedoff, their credit score were below 640 and had 50,000 dollars or less as available bank card credit. 

#Binder
Click the badge to lunch the code on mybinder.org 
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Akomst/-Understanding-Why-Borrowers-Default-Analysis-of-Prosper-Loan-Data/HEAD)
