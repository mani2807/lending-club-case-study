# Lending Club Case Study
> This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
- In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 
- We are using the loan.csv file, given by the company to process and analyse the data, so that we can arrive at the final decision

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Employees with 10+ years of experience tends to take more loans than others, keeping that in mind, Employes having 10 years of experience and < 1 year experience tend to take the major proportion of defaulter list 
- Employee who resides in rented house tend to charged off then in other home ownerships like own, mortgage and  other categories
- Employess with the open accounts between 6 and 9, tend to be defaulted most of the time
- Charged off employees in all the grades (A, B, C, D, E, F, G) has a median salary less then the Fully paid employees, In continuation, Emploees in B and C are charged off more than the other types
- Application type does not have any impact on the loan status, as all the employees who holds the account here are individual accounts
- If the interest rate exceeds beyond the particular value, charged off person increases
- The same trend has been seen with respect to loan amount, when the amount is less, both categories Fully paid and charged off follows the same trend, but when the amount increases, the count charged off slightly overtakes full paid ones
- Borrowers contributing more proportion of income to loan, significantly affects employees to be charged off
- Employees with more bankruptcies are significantly affected, and are defaulted
- Employees with more derogatories are significantly affected, and are defaulted

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python
- Seaborn
- pandas
- numpy
- matplotlib

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad


## Contact
Created by @mani2807 - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
