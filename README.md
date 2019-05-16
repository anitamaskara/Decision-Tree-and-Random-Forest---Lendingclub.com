# Introduction
Using lending data from 2007-2010, trying to classify and predict whether or not the borrower paid back his/her loan in full.

For this project we will be exploring publicly available data from LendingClub.com. 

Lending Club connects people who need money (borrowers) with people who have money (investors). Hopefully, as an investor you would want to invest in people who showed a profile of having a high probability of paying you back. We will try to create a model that will help predict this.

# Data
The data can be downloaded from (https://www.lendingclub.com/info/download-data.action). 

After cleaning the data for NAs, the data contains the following variables:

1. credit.policy: 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.
2. purpose: The purpose of the loan (takes values "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", and "all_other").

3. int.rate: The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0.11). Borrowers judged by LendingClub.com to be more risky are assigned higher interest rates.

4. installment: The monthly installments owed by the borrower if the loan is funded.

5. log.annual.inc: The natural log of the self-reported annual income of the borrower.

6. dti: The debt-to-income ratio of the borrower (amount of debt divided by annual income).

7. fico: The FICO credit score of the borrower.

8. days.with.cr.line: The number of days the borrower has had a credit line.

9. revol.bal: The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).

10. revol.util: The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available).

11.inq.last.6mths: The borrower's number of inquiries by creditors in the last 6 months.

12. delinq.2yrs: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.

13. pub.rec: The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments).

# Techniques used:
- Exploratory Data Analysis - layered histograms, countplots, jointplots, lmplot, 
- Feature engineering - creating dummy variables in pandas 
- Decision Tree model - training, fitting, predicting, evaluating
- Random Forest model - training, fitting, predicting, evaluating
