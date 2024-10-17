Lending Club Case Study
Problem Statement
You are working for a consumer finance company that specializes in lending various types of loans to urban customers. When a loan application is received, the company must decide whether to approve the loan based on the applicant’s profile. There are two types of risks associated with the bank's decision:

Business Loss: If the applicant is likely to repay the loan but is denied, the company loses potential business.
Financial Loss: If the applicant is unlikely to repay the loan (i.e., likely to default), approving the loan may lead to a financial loss for the company.
Objective
The objective of this study is to utilize Exploratory Data Analysis (EDA) to understand how consumer attributes and loan attributes influence the likelihood of default.

Constraints
When a person applies for a loan, the company can make one of two decisions:

Loan Accepted: If the company approves the loan, there are three possible scenarios:

Fully Paid: The applicant has fully repaid the loan, including both the principal and interest.
Current: The applicant is in the process of repaying the loan installments; the tenure of the loan has not yet been completed. These applicants are not labeled as 'defaulted.'
Charged-Off: The applicant has failed to make payments on time for an extended period, indicating that they have defaulted on the loan.
Loan Rejected: The company rejects the loan if the applicant does not meet the required criteria. Since no loan was granted, there is no transactional history for these applicants in the dataset.

Summary
The following files are included as part of this solution:

README.md: This file contains the problem description.
Kunal_Sahu.ipynb: An IPython notebook for performing Exploratory Data Analysis (EDA).
Kunal_Sahu.pdf: A document detailing the analysis and conclusions drawn from the EDA.
Loan.csv: The dataset used for analysis.
