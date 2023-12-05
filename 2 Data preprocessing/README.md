# Borrower reliability research
### Data
Statistics from the bank about the client’s solvency

Data description:
- children — number of children in the family
- days_employed — total length of service in days
- dob_years — client age in years
- education — client’s education level
- education_id — education level identifier
- family_status - marital status
- family_status_id — marital status identifier
- gender — client’s gender
- income_type — employment type
- debt — whether there was a debt to repay loans
- total_income — monthly income
- purpose — purpose of obtaining a loan

### The goal of the project
To build a credit scoring model (a system that evaluates a potential borrower’s ability to repay a loan to the bank), it is necessary to determine whether the client’s marital status and number of children influence the fact of repaying the loan on time.

### Completed tasks

Processing/filling gaps, processing anomalies, converting data types, processing explicit and implicit duplicates, categorizing data, identifying the influence of certain signs on the fact of repaying a loan on time.

The project is finished.

### Key takeaways:

I studied the relationship between the number of children and the repayment of the loan on time, between marital status and the repayment of the loan on time, between the level of income and the repayment of the loan on time, and also studied the influence of the purpose of the loan on the repayment on time:

- The group without children has the highest percentage of loan repayments on time after those with 5 children.
- Clients who are widowers have the highest percentage of loan repayments on time.
- Clients with an income level of 30,001 - 50,000 are the most conscientious and repay the loan on time.
- Clients whose purpose is real estate transactions have the highest percentage of loan repayments on time compared to other groups.

### Libraries used

Pandas
