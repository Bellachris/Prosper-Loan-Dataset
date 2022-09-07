# (Prosper Loan Data Exploration)
## by (Anarado Christiana)


## Dataset

> This dataset is the information of a financial company specializing in loans at low interest rates to the borrowers. It contains information about 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), 
current loan status, borrower income, borrower employment status, borrower credit history, and the latest payment information.
The original data can be found here: https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv
with feature documentation available [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0)


## Summary of Findings

> In the exploration, I found that the distribution of borrowers APR looks multimodal.Most of the distribution is normal with some values that has relatively high frequencies. The Monthly Loan Payment, Loan Original Amount and Stated Monthly Income had long-tailed and skewed distributions which prevent from taking useful insights so I did some transformation by Changing X-ticks to view more exact point of interest, changing bins size to reduce noise in the graph and view data more precisely and using log xscale to make interpretations from the graph easy. Furthermore, The borrower APR has a strong positive relationship with the Borrower Rate. The monthly loan payment has a strong positive relationship with the Loan original amount. The loan original amount is positively correlated with the stated monthly income, which means that borrowers with more monthly income could loan more money. Debt to income ratio is moderately negatively correlated with stated monthly income.

> I found out that Borrower APR was high for less loan original amount and low for high loan amount. Also, Borrower APR and debt to income ratio although tend to go up, had weak correlation whereas borrower APR was weak with negative correlated for monthly income. Their seems to exist a moderate negative correlation between Borrower APR and monthly income which indicate that while both variables tend to go down in response to one another, the relationship is not very strong. Students take the lowest loan original amounts. People with high monthly rate taking high loans. The loan original amount is positively correlated with the stated monthly income, it makes sense since borrowers with more monthly income could loan more money. The loan status for the past dues have a high interest rate.Number of Defaulted loans for Self-employed people are larger than those for Not Employed.

> The Loan original amount tends to increase at 60 month more than that of the 12 and 36 month terms for every income range and there seems to be a strong relationship between term and loan amount (the longer the teerm, the larger the loan). The Borrower rate for defaulter is high for all Employment status group. It is very interesting in each term when the loan original amount increased the medina of 36 and 60 months term increased more than 12 months term median. Finally, the Relation between EmploymentStatus, Status and BorrowerAPR is that Employed people are variegated regarding the Status and BorrowerAPR as they have sometimes high or low borrower rate.


## Key Insights for Presentation

> For the presentation, I just focus on exploring the features selected in order to have an insight of the data such as: Term, Borrower APR, Employment Status, Loan Status, Income Range, Stated Monthly Income and others. I started by showing the distribution of the listed features. Then, I showed the relationship between them. I further investigated the effect of rating on relationship between loan originalamount and Borrower APR, as well as the effect of loan status on relationship between some features.
