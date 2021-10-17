# Regresi-Hazard-Aditif-Lin-Ying

Survival analysis is a statistical procedure for analyzing data with time to a certain event as a response variable. 
If we want to see the effect of the independent variable on the event response time 
variable in the survival analysis, regression analysis is used. One method that can 
be used is Lin-Ying Additive Hazard Regression with coefficient estimation using 
Maximum Partial Likelihood. The regression coefficient is constant so that it can 
be estimated directly and easier to interpret. In addition, this method can assess 
risk (In this study is clinical improvement) and more flexible because no 
proportionality assumption is made. 

This example case used 1 dependent variables and 6 independent variables
1. LOS (Length of Stay) :
   Length of time breat cancer patient hospitalization (hospital care).
2. Status :
   This is censorship. Data is censored if a patient breast cancer dead
   and data is uncensored when a breast cancer patient is declared
   improved and allowed to leavehospital. 
   Categorized into:
   0 = censored (died)
   1 = uncensored (improved)
3. Age :
   Patient's age when admission for hospitalization
4. MS (Marital Status) :
   0 = Single
   1 = Married
5. Treatment :
   0 = Hospitalization/General Condition Improvement
   1 = Radiotherapy
   2 = Chemotherapy
   3 = Surgery
6. Metastasis :
   0 = No metastases
   1 = metastases
7. Anemia :
   0 = No Anemia
   1 = Anemia
8. Comorbidities :
   0 = No Comorbidities
   1 = Comorbidities
