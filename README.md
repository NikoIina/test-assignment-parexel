# Test assignment for Parexel.

##Task 1 (file "solution_resp.ipybn"). 

1. Create logistic regression model with Response (responder / non-responder binomial variable, where response is an event) as dependent variable and Intercept and Treatment as independent variables.

- Report an odds ratio derived from this model of treatment 1 over treatment 2.

- Give a definition of Odds Ratio.

- Give definition of confidence interval

- How it is related with regression coefficients estimated in this model?

2. Create logistic regression model with Response (responder / non-responder binomial variable, where response is an event) as dependent variable and Intercept, Treatment, Gender and Treatment*Gender (interaction of Treatment and Gender) as independent variables.

- Report an 4 conditional odds ratio derived from this model:

treatment 1 vs treatment 2 | Male
treatment 1 vs treatment 2 | Female
Female vs Male | treatment 1
Female vs Male | treatment 2.

- How these 4 odds ratio are related to estimated coefficients?

- Report pvalue for interaction (of Treatment*Gender) significance.

- Give definition of the pvalue.

- Based on this pvalue – do we need to update model (simplify it)? Why?

*Confidence intervals should be derived using Wald method for both items.

Template for the layout:

 

                                                      Logistic regression for subjects response

 

------------------------------------------------------------------------------------------------------------------------------------

                                                                                                                                    

RESPONSE RATE                                                                                                    

 

ODDS RATIO (95% CI): Treatment 1 VS. Treatment 2                               0.59 (0.25, 1.37)                    

ODDS RATIO (95% CI): Treatment 1 VS. Treatment 2 (Female)                      0.59 (0.25, 1.37)                    

ODDS RATIO (95% CI): Treatment 1 VS. Treatment 2 (Male)                        0.59 (0.25, 1.37)                    

ODDS RATIO (95% CI): Female VS. Male (Treatment 1)                             0.59 (0.25, 1.37)                    

ODDS RATIO (95% CI): Female VS. Male (Treatment 2)                             0.59 (0.25, 1.37)                    

INTERACTION P-VALUE                                                            0.0019                               

## Task 2 (file "solution.ipybn").

Please create a table with descriptive statistics for the “Iris Flowers” dataset. 

Requirements for the solution:

- You can use any programming language of your choice for this task.
- Created table should be consistent with the template below (reasonable deviations from layout are acceptable). Numbers in the table should be replaced with actual numbers based on data.
- Alignment of numbers is left up to you but table should be readable and easy to understand.
- Precision should be:
N – integer
Min, max – same precision as in dataset (1 decimal point)
Median, mean, standard deviation - +1 digit to data precision
Percent should be rounded up to 1 digit after decimal point.

The following template should be used (once again reasonable deviations from the template are acceptable)

                                                          Iris Flower Summary                                                  

                                                              All Flowers                                                       

--------------------------------------------------------------------------------------------------------------------------------

                                                Iris Setosa        Iris Versicolor       Iris Virginica             Total        

                                                  N = 1113              N = 1111              N = 1107              N = 3331       

--------------------------------------------------------------------------------------------------------------------------------   

SEPAL LENGTH [CM]                                                                                                                       

  N                                               1113                  1111                  1107                  3331           

  MEAN                                              72                    71                    72                    72           

  MIN                                               94                    95                    94                    95              

  MEDIAN                                            72                    71                    71                    71           

  MAX                                               94                    95                    94                    95              

  STANDARD DEVIATION                                 7.2                   7.4                   6.8                   7.1         

                                                                                                                                     

SEPAL LENGTH (%)                                                                                                             

  < 5                                              192 ( 17.3)           203 ( 18.3)           201 ( 18.2)           596 ( 17.9)

  >=5 AND <6                                       xxx ( xx.x)           xxx ( xx.x)           xxx ( xx.x)           xxx ( xx.x)   

  >=6 AND <7                                       xxx ( xx.x)           xxx ( xx.x)           xxx ( xx.x)           xxx ( xx.x)   

  >= 7                                             xxx ( xx.x)           xxx ( xx.x)           xxx ( xx.x)           xxx ( xx.x) 

 

SEPAL WIDTH [CM]                                                                                                                        

  N                                               1113                  1111                  1107                  3331           

  MEAN                                              72                    71                    72                    72           

  MIN                                               94                    95                    94                    95              

  MEDIAN                                            72                    71                    71                    71           

  MAX                                               94                    95                    94                    95              

  STANDARD DEVIATION                                 7.2                   7.4                   6.8                   7.1         

                                                                                                                                     

SEPAL WIDTH (%)                                                                                                             

  < 3                                              192 ( 17.3)           203 ( 18.3)           201 ( 18.2)           596 ( 17.9)

  >=3 AND <3.5                                     xxx ( xx.x)           xxx ( xx.x)           xxx ( xx.x)           xxx ( xx.x)   

  >=3.5 AND <4                                     xxx ( xx.x)           xxx ( xx.x)           xxx ( xx.x)           xxx ( xx.x)    
