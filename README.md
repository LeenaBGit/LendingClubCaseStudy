# Lending Club Case Study
Lending Club is a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, it makes a decision for loan approval based on the applicant’s profile. If the applicant is likely to repay the loan, then not approving the loan will result in a loss of business to the company. If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company. The primary objective of this case study is to assist Lending Club in mitigating financial losses from these risks by identifying risky loan applicants.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)
* [Contributor](#contributor)


## General Information

- The project aims to identify the driving factors behind loan default, i.e. the variables which are strong indicators of default and thus identify risky loan applicants
- The dataset contains information about past loan applicants and whether they ‘defaulted’ or not


## Conclusions
- The company should be careful when giving loans of the following nature:
1. Short-term loans with a duration of 36 months
2. Loan grade B or C
3. Loan subgrade B5, C1, B4 or B3
4. Debt consolidation is the primary loan purpose
5. Interest rate between 13% to 17%
6. Applied for Loan amounts of 15000 USD and above
7. Loans taken towards the end of the year

- The company should be careful when giving loans to applicants with the following characteristics:
1. Employed for more than 10 years
2. Live in rented or mortgaged houses
3. Made no inquiries in past 6 months(excluding auto and mortgage inquiries)
4. With annual salary less than 40000 USD
5. Live in California, Florida or New York
6. Have very high debt-to-income ratios


## Technologies Used
- Python - version 3.11.4
- Numpy - version 1.24.3
- Pandas - version 2.0.3
- Matplotlib - version 3.7.2
- Seaborn - version 0.12.2


## Acknowledgements
- This project was inspired by live sessions of UpGrad on EDA and Data Visualisation by Shivam Garg
- UpGrad tutorials on Exploratory Data Analysis (EDA) and Data Visaulisation


## Contributor
- Leena Barua
