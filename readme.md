# Project: Prosper Loan Data
## by Eleftherios Kokkinis


## Dataset

>Our dataset contains information for about 114.000 loans and 84 different features for each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. First we intent to wrangle and clean some of the issues that our data may have. Then we will pose some questions which we will attempt to answer by performing exploratory data analysis practices and creating several visualizations.


## Summary of Findings

> Our goal in this project was to determine important factors that can affect the status of a loan (`Defaulted`,`Completed`,`Charged off`) as well as the score that it gets from Prosper, `ProsperScore`. Finally we looked into what factors may affect the APR of the Borrowers as well as the size of the loans. All in all, we realized that lower APR means higher ProsperScore while Large Loan Amounts also bear a higher ProsperScore and come from people with high incomes. This is likely the reason that we spotted a weak negative relation between APR and high Loan Amount. In addition, we spotted a positive relation between the Estimated Loss and the APR and consequently a negative one with the Prosper Scores. Finally, it was made clear that the Defaulted, Changed off and Completed Loans had a higher Estimated Loss and feature lower Prosper Score.


## Key Insights for Presentation

> The main insights that will be presented are the underlying reasons that a loan gets a high or low Prosper Score and which loans are more likely to get specific status. In addition, the relations of the APR and how its value affects other parameters is an important insight that will be included in the slide show. Before these final insights are presented, we will show a few key statistics and information about individual variables.


## References
> - Towards Data Science
  - Stack Overflow
  - Seaborn/Maplotlib docs
  - Udacity Knowledge Platform