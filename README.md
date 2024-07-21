# Project Name : Lending Club Case Study
This is a data science project focused on risk analytics in the banking and financial services sector, utilizing the Lending Club dataset to predict loan defaults.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

- This project is focused on risk analytics within the consumer finance sector, leveraging historical loan data to enhance decision-making processes related to loan approvals. The primary goal is to predict loan defaults using exploratory data analysis (EDA) on a dataset of past loan applicants.

    #### Background

    This Company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.
    If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss.

    #### Business Problem

    The project aims to address the challenge of credit loss in the banking and financial services sector. Specifically, it focuses on identifying risky loan applicants who are likely to default on their loans. 

    #### Dataset 

    The dataset is a csv file with the loan data for the Lending Club. Also an excel file having data_dictionary.

    #### Approach

    ##### Step-by-Step Analysis:

    - **Data Sourcing**: Load the provided csv file data.
    - **Data Inspection**: Understanding the given data.
    - **Data Cleaning**: Address missing values, outliers, and data inconsistencies.
    - **Data Visualization and Analysis**: Perform univariate, segmented univariate and bivariate analysis.
    - **Insights and observations** : Derive insights and suggest actionable recommendations.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Major Driver variables which are strong indicators of default are:
    - **int_rate** (Intrest rate)
    - **purpose** (loan purpose)
    - **dti** (Debt-to-Income Ratio)
    - **grade** (loan grade)
    - **Pub_rec_bankruptcies** (public record bankruptcies)
    - **emp_length** (Employment length)
   
    
- Details on the above variables and other aspects:
    - Borrowers with 60 month term loan has higher chance of defaulting.
    - Borrowers with loan Grade F,D,G have higher chance of defaulting with G the highest.
    - Borrowers who take small_business loan have higher chance of defaulting.
    - Borrowers with Public Recorded Bankruptcy has higher chance of defaulting.
    - Borrowers with experience of 10+ years are more likely to default.
    - Borrowers with High interest specifically above 17.5 are more likely to default.
    - Borrowers loan in dti range of 19-25 have higher chance of defaulting.
    - Borrowers who are on RENT has higher chance of defaulting compared to Mortgage or own house.
    - Borrowers with working experience 10+ years has higher chance of defaulting.
    

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Anaconda Navigator - version 2.5.2
- Jupyter Notebook - Version 7.0.8
- Jupyter Lab - Version 4.0.11
- pandas - version 2.1.4
- matplotlib - version 3.8.0
- seaborn - version 0.12.2
- plotly - version 0.12.2


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was inspired by UpGrad IIITB Programme as a case study for the Machine Learning and Artificial Intelligence course.


## Contact
Created by [@Sinhakrrajesh] - feel free to contact me!


## License 
 This project is open source and available to all.