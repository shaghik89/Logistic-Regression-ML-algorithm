# Logistic-Regression-ML-Algorithm
What is Regression?
Regression Analysis is a predictive modeling and it estimates relationship between a dependent(target) and independent(predictor) variables. 

Logistic Regression:
Logistic Regression produces results in a binary type so it is implemnted to predict the outcome of a categorical dependent variable. Hence, the outcome must be discrete/categorical such as: Yes/No, 0 or 1, True or False, High/Low.
By using Sigmoid curve it converts any value to discrete values which logistic regression requires. 
Concept of Threshold value is also used so with this, the threshold value indicates the probability of winning or losing.
For instance: suppose we have 0.8 how we will consider it 1 or 0? it dependes on threshold value suppose threshold value = 0.5 since 0.8 > 0.5 so it will comsider as 1. 
Logistic Regression equation is derived from the straight line equation so:
#straight line equation : Y=C+B_1X_1 + B_2 X_2 +...                                   range is from -(infinity) to (infinty)
logistic regression equation from straight line : Y=C+B_1X_1 + B_2 X_2 +...           range is from 0 to 1
Now we get Y between 0 and infinty : Y    Y=0
                                     1-Y  Y=1 then infiniy 

Final Logistic Regression equation:   log (Y/1-Y) which Y=C+B_1X_1 + B_2 X_2 +...      
               
Logistic Regression:value of Y or the varibale we need to predict should be dsicrete and it is categorical variable
Logistic Regression solve the classification problems
 
 Here we explore titanic dataset about people who survived and who did not survive 
 We can analyze factores made people more likely to survive in the sinking of Titanic?
 
 For implemenation of Logistic regression following steps are required: 
 Collecting Dta
 Data Wrangling (preprocessing)
 Analyzing Data
 Train & Tst Data
 Accuracy evaluation


