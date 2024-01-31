# Data Pre-processing:
cleanse and analyze the data using Python (pandas, plotly, display, HTML).

## Borrower reliability
The customer is the credit department of a bank. We need to understand whether the marital status and the number of children of the client affects the fact of loan payment on time. Input data from the bank - statistics on the solvency of clients.

The results of the research will be taken into account when creating a credit scoring model - a special system that assesses the ability of a potential borrower to pay back a loan to the bank.

### General summary
In order to assess the reliability of borrowers, a survey was conducted and answers to certain key questions were provided. Following the responses, the findings were as follows:
Data preprocessing work was carried out for the study: anomalous values and omissions were removed, the register and loan purpose data were unified, salary ranges were categorised, etc.

The study worked on estimating the dependence of loan return on time on several factors. Thanks to the use of the summary table function, it was possible to assess the influence of the following parameters on the reliability of borrowers:

- number of children - rather influential (for people with 0-2 children: the more children, the higher the debt),
- marital status - affects (borrowers who are or have been officially married are more reliable),
- income level - for categories B and C: the lower the income, the higher the debt,
- purpose of the loan - affects (car loans are poorly repaid, mortgages are much better).
