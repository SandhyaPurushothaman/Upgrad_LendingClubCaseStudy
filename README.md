# Lending Club Case Study
> In this project, we will explore risk factors associated with Lending Club loans using an Exploratory Data Analysis (EDA) approach. Our goal is to identify patterns and insights that can help in understanding borrower behaviour and creditworthiness.


## Table of Contents
* Lending Club Case Study Problem Statement
* Python, Jupyter Notebook, Lumpy, Matplotlib, Seaborn
* Risk areas highlighted, and key suggestions recommended
* Niharika Patne and Sandhya Purushothaman

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Lending Club is a peer-to-peer lending platform that connects borrowers and investors.By analyzing loan data, we can uncover critical risk factors that influence loan performance and borrower defaults. This understanding is essential for effective risk management.
- Using Python and Python-based plotting mechanisms, we need to identify risks and provide recommendations to reduce defaulters in loan-payments.
- The objective is to analyze historical loan applicant data to identify patterns of default risk, enabling decisions on loan approval, modification, or denial based on the applicant's willingness to repay.
- Loan.csv provided on the Upgrad learning portal

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- It is very clear that the bank needs to revisit its interest rate. Loan takers have a tendency to not pay back due to financial load owing to increased interest rates. This raises alarm towards the current loans, as the interest rate is very high.
- On an average, the loans amounting to high values have higher risk of being Charged Off as compared to the ones amounting to low value. This provides an indicate to the lending club that any loan application amounting to high value should be scrutinized further, with more verification levels.
- As income increases, the distribution of DTI ratios tends to compress and lower, suggesting that higher-income earners generally manage lower DTI ratios. This is likely because their higher income provides more financial leeway in managing debt.
- The frequency of charged off loans increases as the grade worsens, with the highest numbers seen in grades D through G. This trend highlights the increased risk associated with these grades. Grade G, despite its lower volume of loans, has a significant proportion of charged off loans, underscoring the high risk associated with lending to borrowers in this category. Charge offs for Grade A are comparatively low with the amount of Fully paid loans.
- Certain loan purposes like small_business and renewable_energy show a relatively higher proportion of loans being charged off compared to others.This suggests these types of loans carry a higher risk of default.
- Loan-takers prevailing from states Tennessee and Idaho, have a tendency to default as compared to loan-takers from other states
- Applicants with emp_title 'Loyola University Medical Center', 'national grid', 'Lutheran Family Services of VA', and 'BeyondTrust Software' and few such are more delinquent as compared to employees with other titles. This is an indicator to the lending club to raise a risk, scrutinize pay-backs and perform continuous follow-ups for loans taken by employees of this title. And also, while issuing new loans to employees of such titles, the lending club can perform thorough background checks to verify the pay-back capability.
- the Purposes for loan owing to 'debt_consolidation' and 'credit_card' are the ones with loan takers having higher DTI values. On an average the higher DTI maps to the loans being Charged Off. This concludes that when the Lending Club comes across Purposes listed above, probably the loan should not be approved, or the interest rates should be high. It also indicates high risk for the Current loans falling under these Purposes.
- 'funded_amnt', 'installment' - Highly correlated indicating that as the loan amount increases, the installment payments increase almost proportionally.funded_amnt and installment have a moderate positive correlation (0.27) with annual_inc. This suggests that borrowers with higher incomes tend to take out larger loans, which subsequently have higher installments.Dti shows lower correlation with all the three variables.
- Loan Amount and Installments: The direct correlation suggests that as the loan amount increases, so does the financial burden on the borrower, which can impact the likelihood of repayment. Income Insights: Higher incomes do not necessarily correlate with higher loan amounts, which might suggest a conservative borrowing behavior among higher earners or possibly that they are less represented in the data. Risk Factors: Higher DTIs and higher loan amounts seem to correlate with a greater likelihood of a loan being charged off. Lenders might use this information to adjust credit risk assessments or loan terms. Debt Management: The broad distribution of DTIs and its relative independence from income suggests that debt management and financial planning are critical across all income levels.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 3.9
- Matplotlib
- Seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was an assignment from Upgrad so as to familiarise oneself with real-life use-cases and problems on how raw data should be approached, and what can be inferred from it.


## Contact
Created by GitHub user : SandhyaPurushothaman

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->