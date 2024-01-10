# IEEE-CIS Fraud Detection

In this notebook, we will work on the IEEE-CIS Fraud Detection competition. Our aim is to train a machine learning model to predict the probability that an online transaction is fraudulent.   

Categorical Features - Transaction:
- ProductCD
- card1 - card6
- addr1, addr2
- P_emaildomain
- R_emaildomain
- M1 - M9

Categorical Features - Identity:
- DeviceType
- DeviceInfo
- id_12 - id_38

The TransactionDT feature is a timedelta from a given reference datetime (not an actual timestamp). 
Agenda:  
1. Importing Necessary Libraries 
2. Data Loading 
3. Understanding, and Cleaning 
4. Data Preprocessing 
5. ML Modeling
6. Conclusion
