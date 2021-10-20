# Logistic-Regression-ML-Algorithm
What is Regression? <br />
Regression Analysis is a predictive modeling and it estimates relationship between a dependent(target) and independent(predictor) variables. <br />

Logistic Regression:<br />
Logistic Regression produces results in a binary type so it is implemnted to predict the outcome of a categorical dependent variable. Hence, the outcome must be discrete/categorical such as: Yes/No, 0 or 1, True or False, High/Low. <br />
By using Sigmoid curve it converts any value to discrete values which logistic regression requires. <br />
Concept of Threshold value is also used so with this, the threshold value indicates the probability of winning or losing. <br />
For instance: suppose we have 0.8 how we will consider it 1 or 0? it dependes on threshold value suppose threshold value = 0.5 since 0.8 > 0.5 so it will comsider as 1.  <br />
<br />
Logistic Regression equation is derived from the straight line equation so: <br />
<br />

  h<sub>&theta;</sub>(x) = &theta;<sub>o</sub> x + &theta;<sub>1</sub>x
straight line equation : Y=C+B_1X_1 + B_2 X_2 +...                                   range is from -(infinity) to (infinty) <br />
logistic regression equation from straight line : Y=C+B_1X_1 + B_2 X_2 +...           range is from 0 to 1 <br />
Now we get Y between 0 and infinty : Y    Y=0 <br />
                                     1-Y  Y=1 then infiniy <br />

Final Logistic Regression equation:   log (Y/1-Y) which Y=C+B_1X_1 + B_2 X_2 +...      <br />
 <br />              
Logistic Regression:value of Y or  predicted variable should be dsicrete and categorical variable and it solved the classification problems  <br />
<br />

 Here we explore titanic dataset about people who survived and who did not survive <br />
 We can analyze factores made people more likely to survive in the sinking of Titanic? <br />
 
 For implemenation of Logistic regression following steps are required: <br />
 Collecting Data <br />
 Data Wrangling (preprocessing) <br />
 Analyzing Data <br />
 Train & Test Data <br />
 Accuracy evaluation <br />


