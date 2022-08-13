# Logistic_Regression

## OESON - Case Study Domain - Banking/Loan focus

Lower NPA (Non Performing Asset) Business challenge/requirement

PeerLoanKart is a NBFC (Non-Banking Financial Company) which facilitates peer to peer loan.

It connects people who need money (borrowers) with people who have money (investors). As an investor, you would want to invest in people who showed a profile of having a high probability of paying you back. You as a ML expert create a model that will help predict whether a borrower will pay the loan or not.

## Key Issues

Ensure NPAs are lower - meaning PeerLoanKart wants to be very diligent in giving Loans to borrower.

Considerations: NONE

## Data

file loan_borrower_data.csv 

## Fields in Data

* credit.policy: 1 if the customer meets the credit underwriting criteria of PeerLoanKart, and 0 otherwise

* purpose: The purpose of the loan (takes values "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business" and "all_other").

* installment: The monthly installments owed by the borrower if the loan is funded.

* log.annual.inc: The natural log of the self-reported annual income of the borrower.

* dti: The debt to income ratio of the borrower (amount of debt divided by annual income)

* fico: The FICO credit score of the borrower.

* days.with.cr.line: The number of days the borrower has had a credit line.

* revol.bal: The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).

* revol.util: The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available).

* inq.last.6mths: The borrower's number of inquiries by creditors in the last 6 months.

* delinq.2yrs: The number of times the borrower has been 30+ days past due on a payment in the last 2 years.

* pub.rec: The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments).

* not.fully.paid: This is the output field. Please note that 1 means borrower is not going to pay the loan completely.

## Business Benefits

Increase in profits up to 20% as NPA will be reduced due to loan disbursal for only good borrowers.
