# Exploring Loan Data from Prosper
## by Aastha Arora


## Dataset

Prosper is a peer-to-peer lending marketplace. The [data set](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1554486256021000) contains 113,937 loans (last updated 03/11/2014) with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. The variable definitions for all features in the dataset available [here](https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1554486256024000)


## Summary of Findings

In the exploration, I found that there was a strong relationship between Borrower ARP and Prosper Rating. For a borrower to get a good (low) APR rate, Prosper Rating should be high.

The borrowers with low prosper score also have low prosper rating while the borrowers with high prosper score also have high prosper rating.

For different values of Prosper Ratings, there is a relationship between Loan Original Amount and Borrower APR. For 'HR' rating, borrowers get a smaller loan at comparitively high APR. With a Prosper Rating of 'AA', a borrower is eligible to get a loan of any amount and also pays lower APR on the loan.


## Key Insights for Presentation

For the presentation, I focus on just the influence of the effect of different features on the Borrower APR. I start by introducing the Borrower APR and plot distributions of main features. Next, I explore the relationship between different variable and plot bivariate vizualizations.

I use box plots, violin plots, scatter plots and clustered bar charts to analyzed how Debt To Income Ratio, Stated Monthly Income and Loan Original Amount affect the Borrower APR. Towards the end, I explore the effect Loan Status and Income Range on Borrower API.
