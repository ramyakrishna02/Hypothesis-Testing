# Hypothesis-Testing

It is a statistical method that is used in making statistical decisions using experimental data. It is basically an assumption that we make about the population parameter.

-> Eg.. Votes for the politician will be more than 60%
    - (null hypo) H0 : Population of votes <= 60%
    - (alter hypo) H1 : Population of votes > 60%
    
- Null Hypothesis H0
    - Argument made so far, or hypothesis saying that there is no change or difference
- Alternative Hypothesis H1
    - New argument, that is a hypothesis that you want to prove with solid ground obtained from sample
    
### Procedure of Hypothesis Testing
The steps for hypothesis tests;
1. Define null & alternative hypothesis
2. Identify the test statistic to be used for testing the validity of the null hypothesis
3. Decide the significance value (Alpha). Generally taken as 0.05
4. Two methods from here:

    1st
    -> comapre t-statistical value and t-critical value
    - if t-statistical value > t-critical value .. reject null hypothesis H0 i.e., accept alternative hypothesis
    - if t-statistical value < t-critical value .. accept null hypothesis H0

    2nd
    -> p value method
       (probability value..) 
    - if p value > 0.05 -> accept null hypothesis
    - if p value < 0.05 -> reject null hypothesis i.e., accept alternative hypothesis
    
    
### Test Statistics used in the assignment
  - Two sample T-test
  - One way ANOVA test
  - Chi-Square test

## Packages used
- Pandas
- Stats from Scipy
