# Lending Club Case Study
> Identify the risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicant's using EDA is the aim of this case study

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- This is finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface
- It is a case study on a bank data to analyse the risks involved
- Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders.


## Conclusions
- Univariate Analysis
    - Number of 36 months loan are higher than 60 months loan
    - Employees with 10+ years of total experience availed maximum number of loans
    - Significantly higher number of loans are taken for debt consolidation purpose
    - Most loans are taken from people whose house ownership status is either rent or mortgage
    - Higher number of loans are taken from non verified sources
    - Loan issuance are increasing from July 07 to December 11
    - CA state has maximum loan applications

- Segmented Univariate Analysis
    - There is no significant difference for loan amount vs loan status, but the number of Charged Off people are in the bucket of 5000 till 16000
    - People in higher annual income range have lesser chances of Charged off than Fully Paid
    - People in higher funded amount have more chances of Charged off than Fully Paid

- Bivariate Analysis
    - People in grade B and C are having more chances of charged off
    - People in 36 months load tenure have more chances of charged off
    - People having higher tendency of being charged off, if the loan purpose is debit consolidation, other categories, small business and credit card
    - People having higher tendency for doing charged off, if their home ownership is rented or mortgage
    - People belongs to experience group of 1 to 3 years and more than 10+ years are having more chances of Charged off
60 months loan term see significantly large percentage of defaulters
    - People with annual income in the range of 20000 to 60000 are having more chances of Charged Off
    - People availed loan with interest range between 10 t0 15 are having more chances of Charged Off
    - People with no verification status are more prone to be Charged off, and hence we need to ensure proper verification for people before allocating the loan
    - Charged off chances are higher for people in the last month of every year. Reason could be Holidays or any sort of Crisis or more expenses due to vacation plans

- Correlation
    - The loan amount, funded amount and funded amount inv are positively correlated
    - DTI ratio is negatively correlated with annual income, which means higher the annual income lower is the DTI ratio
    - If Installment is higher, then the loan amount is also higher and interest rate is similar in both the factors

## Technologies Used
- pandas - version 2.2
- numpy - version 1.26.3
- matplotlib - version 3.8.2
- seaborn - version 0.13.2

## Acknowledgements
- This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course

## Contact
Created by [] - feel free to contact me!
