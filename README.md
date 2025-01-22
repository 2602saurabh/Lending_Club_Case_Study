# Lending Club Case Study
> This is a case study to understand and identify the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. We are using data of past customers.


## Table of Contents
* [General Info](#general-information) 
* [Technologies Used](#technologies-used) 
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Solving business problem using EDA.
- This is part of our course work at Upgrad ML & AI course.
- The business problem is determining which consumer attributes and loan attributes influence the tendency of default.
- The dataset used is the complete loan data for all loans issued for the time period from 2007 to 2011.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
There were 39,717 records in the dataset. All of them had unique / different id and member id. Out of these 5,627 were charged off records which were used for further analysis. There were 111 variables to start with which I reduced to 46 by first removing columns/variables which had missing values for all records and then removing those which had same value for all records. Thus we were left with 5,627 records and 46 columns.
### For charged off accounts
- Majority of loans were from 3,000 to 20,000 and there were some outliers (approx. 200 out of 5,627) who had loan amount over 32,000.
- The most frequent purposes for taking loan were Debt consolidation, credit card, small business, and other which accounted for approx. 80% of all.
- People with 10+ years are the single largest group, and along with low experienced (<1, 1, 2 and 3 years) make up for approx. 65% of charged off accounts.
- All customers with charged off accounts carried a high debt payment to income ratio (dti) ranging from 3 to 30 for over 90% of the loans, so this can act as a big red flag when processing the loan.
- In grade E, F and G majority of the loans were given in a higher band (loan amount approx. 15-25k). There were lesser outliers because of this in these 2 bands. 
- In grades A, B, C and D majority had lower loan amounts (5k -15k) but had lot of outliers (loan amount above 30k).
- As grade decreases (A being highest and F being lowest), the interest rate increases.
- For grade A, majority of charged off accounts had interest rate from 6.0 - 7.5%, while G and F had interest rates up to 22.5%. 
- There are lot of outliers in grades C and D. The outliers are on the lower side as well.
- People who were given an attractive (lower) interest rate also default.
- In every grade there were lots of people who were above max annual income for their grade and were charged off.
- We can also infer that if someone is above max income for their grade they are more likely to not repay (and be charged off subsequently).

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.12.7
- Jupyter notebook 

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Resources who worked on this project : Saurabh Gupta 2602.saurabh@gmail.com and Shagufa Nausheen 9sheen12@gmail.com



## Contact
Created by [@2602saurabh] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
