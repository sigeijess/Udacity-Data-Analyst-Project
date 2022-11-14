# Prosper Loan Data Exploration

## by Jesse Kimaru

## Prosper Dataset

This data set contains information on peer to peer loans facilitated by credit company Prosper. There are 113,937 
loans with 81 variables. For the purpose of this investigation I've taken the following variables: Term,
LoanStatus, BorrowerRate, ProsperRating (Alpha), ListingCategory (numeric), EmploymentStatus,
DelinquenciesLast7Years, StatedMonthlyIncome, TotalProsperLoans, LoanOriginalAmount, LoanOriginationDate, 
Recommendations and Investors.

## Summary of Findings

Majority of the borrowers are employed while all other categories are a small part of borrowers. In small group 
full time have the highest number of borrowers followed by self employed respecively. 
Most of the loans in the data set are actually current loans. Past due loans are split in several groups based on
the length of payment delay. Other big part is completed loans, defaulted loans compromise a minority, however 
chargedoff loans also comporomise a substanial amount. We can see that the most frequent rating among defaulted 
loans is D, while most frequent rating amongst completed is also D followed by A respectively in Status and 
Prosper Rating.
Lower ratings seem to have greater proportions of individuals with employment status Not Employed, Self-employed,
Retired and Part-Time. Except for the lowest ratings defaulted credits tend to be larger than completed. Most of
the defaulted credits comes from individuals with low Prosper rating.
Generally we can state that defaulted credits tend to be smaller than completed credit score. 

## Key Insights for Presentation

The plots chosen shows distribution of main variables, Loan status, monthly income, Prosper rating and i have
tried to tell a story on what are the major predictors for loan status and how the Prosper rating variables works.
