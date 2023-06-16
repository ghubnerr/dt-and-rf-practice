# Random Forest and Decision Tree Practice Project 
![Capture](https://github.com/ghubnerr/dt-and-rf-practice/assets/91924667/597e26c5-6482-4868-bfbc-a6ca7a2de8de)


Data collected from [LendingClub.com](www.lendingclub.com). 
This model has the purpose of evaluating the likelihood that someone who borrows money will pay you back, given their profile by using lending data from 2007-2010.
 
Data can be downloaded from [here](https://www.lendingclub.com/info/download-data.action) -> Download .csv provided version.

### Column data:
* credit.policy: 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.
* purpose: The purpose of the loan (takes values "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", and "all_other").
* int.rate: The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0.11). Borrowers judged by LendingClub.com to be more risky are assigned higher interest rates.
* installment: The monthly installments owed by the borrower if the loan is funded.
* log.annual.inc: The natural log of the self-reported annual income of the borrower.
* dti: The debt-to-income ratio of the borrower (amount of debt divided by annual income).
* fico: The FICO credit score of the borrower.
* days.with.cr.line: The number of days the borrower has had a credit line.
* revol.bal: The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).
* revol.util: The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available).
* inq.last.6mths: The borrower's number of inquiries by creditors in the last 6 months.
* delinq.2yrs: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.
* pub.rec: The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments).

## Model Performance Evaluation Comparison
### Decision Tree Classification Report
Decision Tree yielded 75% accuracy.

![Capture](https://github.com/ghubnerr/dt-and-rf-practice/assets/91924667/71a202c5-3ff0-46a9-9814-de31558a8582)

### Random Forest Classification Report
100 enumerators yielded accuracy of 84%

![Capture](https://github.com/ghubnerr/dt-and-rf-practice/assets/91924667/27543c17-7422-49c5-ae35-7590aa95689a)

### Credit for the Project Ideation
Jose Portilla, from [PierianData.com](http://www.pieriandata.com).
