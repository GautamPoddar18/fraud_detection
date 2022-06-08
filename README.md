

## Table of Contents
* [Business Understanding](#business-understanding)
* [Objective](#objective)
* [Key Assumption](#key-assumption)
* [Conclusions](#conclusions)
* [Libraries](#libraries)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## Business Understanding
We are working for a consumer finance company which specialises in lending various types of loans to urban customers.
When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.
Two types of risks are associated with the bank’s decision:
- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
## Objective 
The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment. 

## Key Assumption 
- Missing employee length as Zero. 
- pub_rec_bankruptcies empty value as Zero 
- Set the outliner limit as 95% 
- Excluded the columns which is not a driving factor and not have more than one unique values.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- Higher the Interest rate and higher the loan amount is causing the Higher charged off . 
- Higher Charged off is happening between Sep, Oct, Nov and Dec Month it based on loan issued date. 
- Small Business purpose loan has high impact on Charged Off. 
- 60 Months payments loans has high impact of charged-off. 
- lower income range is the more risky when it comes to loan repayment. 
- Higher instalments has more risks of charged off. 
- Applicants having public record bankruptcies has more risk of charged off.

## Libraries
- warnings
- numpy 
- pandas
- matplotlib
- seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was based on live uprgrad session on EDA and Case Study Anaylsis

## Contact
Created by [@GanesamoorthiM] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
