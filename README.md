# Bank-loan-risk-analysis-with-current-and-previous-application-data
This case study aims to identify patterns which indicate if a client has difficulty paying their installments which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. This will ensure that the consumers capable of repaying the loan are not rejected. Identification of such applicants using EDA is the aim of this case study.
In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment.
Business Understanding
The loan providing companies find it hard to give loans to the people due to their insufficient or non-existent credit history. Because of that, some consumers use it as their advantage by becoming a defaulter. Suppose you work for a consumer finance company which specialises in lending various types of loans to urban customers. You have to use EDA to analyse the patterns present in the data. This will ensure that the applicants capable of repaying the loan are not rejected.

When the company receives a loan application, the company has to decide for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.

The data given below contains the information about the loan application at the time of applying for the loan. It contains two types of scenarios:

The client with payment difficulties: he/she had late payment more than X days on at least one of the first Y instalments of the loan in our sample,

All other cases: All other cases when the payment is paid on time.

When a client applies for a loan, there are four types of decisions that could be taken by the client/company):

Approved: The Company has approved loan Application

Cancelled: The client cancelled the application sometime during approval. Either the client changed her/his mind about the loan or in some cases due to a higher risk of the client he received worse pricing which he did not want.

Refused: The company had rejected the loan (because the client does not meet their requirements etc.).

Unused offer:  Loan has been cancelled by the client but on different stages of the process.

**Education type distribution for defaulters and non-defaulters**


![image](https://github.com/GunjanBhardwaj2612/Bank-loan-risk-analysis-with-current-and-previous-application-data/assets/123326933/5877bd94-4052-4324-a37f-b839c1e122b6)



**Family status distribution for defaulters and non-defaulters**


![image](https://github.com/GunjanBhardwaj2612/Bank-loan-risk-analysis-with-current-and-previous-application-data/assets/123326933/dc1ad28d-9996-4cd6-bea2-1ba55bc7575f)



**Annuity amount distribution for defaulters and non-defaulters**



![image](https://github.com/GunjanBhardwaj2612/Bank-loan-risk-analysis-with-current-and-previous-application-data/assets/123326933/6314e36f-1309-4a20-bbe1-039ddc7411de)



**Credit amount distribution for defaulters and non-defaulters**


![image](https://github.com/GunjanBhardwaj2612/Bank-loan-risk-analysis-with-current-and-previous-application-data/assets/123326933/4481c7a3-51d0-4637-b634-273d4d572681)



**Income distribution across genders - defaulters**


![image](https://github.com/GunjanBhardwaj2612/Bank-loan-risk-analysis-with-current-and-previous-application-data/assets/123326933/9f17e3b8-5334-42ec-8040-7a55030028e2)


**Income distribution across genders - non-defaulters**


![image](https://github.com/GunjanBhardwaj2612/Bank-loan-risk-analysis-with-current-and-previous-application-data/assets/123326933/38d2935b-d3f8-4c23-bdb6-2643e6e8400a)



**Correlation across various numerical criterias**


![image](https://github.com/GunjanBhardwaj2612/Bank-loan-risk-analysis-with-current-and-previous-application-data/assets/123326933/a04ec667-f900-452c-93ad-a1c343fe54fd)


Analysis-
high correlation b/w AMT_CREDIT & AMT_ANNUITY, AMT_ANNUITY & AMT_GOODS_PRICE , AMT_GOODS_PRICE & AMT_CREDIT
Medicore relationship of AMT_CREDIT, AMT_ANNUITY, AMT_GOODS_PRICE with AMT_INCOME_TOTAL


**Coorelation b/w income and credit for defaulters and non-defaulters**



![image](https://github.com/GunjanBhardwaj2612/Bank-loan-risk-analysis-with-current-and-previous-application-data/assets/123326933/25d948e4-cdc0-43b8-b7d4-6d53c2c72693)


Analysis:
Defaulters - We can slightly figure out that the values are more concentrated on the lower income and lower credit of the loan. That means as the income is increased, the amount of loan is also increased. This is true for both the genders.
Non defaulters - We can hardly figure out any pattern out of this.



**Relation b/w application amount and credit amount across various contract status**


![image](https://github.com/GunjanBhardwaj2612/Bank-loan-risk-analysis-with-current-and-previous-application-data/assets/123326933/13215769-5837-468b-8d64-92dd97402e58)



Analysis: We can see that the applications are more concentrated on the lesser amount and so as the credited amount. Also, the credited amount is increased with respect to the application amount.


**Current loan defaulter status with respect to previous loan application status and income group**



![image](https://github.com/GunjanBhardwaj2612/Bank-loan-risk-analysis-with-current-and-previous-application-data/assets/123326933/7e140520-74d4-4b5a-9661-7304f34b7a03)


Analysis : The income status is more or less similar for previous defaulters and application status
