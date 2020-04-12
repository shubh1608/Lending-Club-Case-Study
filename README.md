# Lending Club CaseStudy

#### Project Status: [Completed]

## Project Intro/Objective
Risk Analysis for a Consumer Finance company where we want to help company to take decisions to offer loan to a particular applicant or not. Risks are identified based on the applicant's profile.

### Partner
* Swayam Nanda, email: nanda.swayam@gmail.com

### Methods Used
* Exploratory Data Analysis
* Data Visualization

### Technologies
* Python
* Pandas 
* Jupyter

## Project Description
You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
   * If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
   * If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

The data given contains the information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

In this case study, we used EDA to understand how consumer attributes and loan attributes influence the tendency of default.
 
When a person applies for a loan, there are two types of decisions that could be taken by the company:
   * Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
      * Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
      * Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
      * Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

   * Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)


## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. You can find the data at- "loan.csv" within this repo.
3. Refer Data dictionary- "Data_Dictionary.xlsx" for in depth understanding of the dataset.
4. Go through the notebook for detailed analysis.

## Contact
* Shubham Patel, email: shubhampatel1608@gmail.com, mobile: 8103856241
