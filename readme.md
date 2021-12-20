# (Prosper Loan Data Analysis)
## by (Mohammad Aamir)


## Dataset

> This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. The dataset and feature documentation available can be found [here](https://www.kaggle.com/imsparsh/lending-club-loan-dataset-2007-2011)



## Summary of Findings

> After analysing all the related features available in the ProsperLoan Dataset. Our analysis was primarily focussed at identifying variables affecting BorrowerAPR. BorrowerAPR is a continuous variable, hence histogram is suitable choice to analyze its distribution.Since it did contain significant number of NA’s, missing values had to be eliminated before exploring its relation with other variables.I studied effect of several features on BorrowerAPR. CreditGrade is not populated for listings after 2009, otherwise ProsperRating is populated for listings after 2009, so comnined thes as one feature. and I had to handle lots of missing values before implementing our bivariate analyasis. While exploring the relation between BorrowerAPR and its potential predictors, I found out that ProsperRating, Term and loan original amount impact it significantly. On the other hand, the effect of other variables like DebtToIncomeRatio, BorrowerState and AmountDelinquent on BorrowerAPR is not remarkable.

> Outside of the main variables of interest, I found positive relationship between prosper rating and loan original ammount and prosper score borrowers with better rating also have larger loan amount. A positive correlation was observed between Monthly Loan Payment,stated monthly income and Loan Original Amount, which make sense with higher income you could loan more money and will pay more monthly. There was also a positive relationship between the percentage of people who own a home with verified income and the Term and prosper rating. with the higher term and rating there a higher percentage of home owners with verified income.



## Key Insights for Presentation

> For the presentation, I focus on just the features tha have a strong effect on the borrower APR which are borrower prosper rating, original loan ammount and Term. First I started with histogram plot were created to visualize the distribution on borrower's APR. After exploring all possible variables related to BorrowerAPR. then I showed the relationship between borrower APR and Prosper rating followed by the correlation between Borrower APR and Loan Original Amount. Finaly the effect of Prosper rating on relationship between borrower APR and term.
