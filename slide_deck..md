##  Prosper Loan Data Exploration
 
##### By Nada Alruwaythi

##### Investigation Overview
* In this investigation, I wanted to figure out two things:

- 1- The variables that can be utilized to forecast credit default.
- 2- What variables determine Prosper's rating.

Dataset Overview
This data set contains 113937 loans with 81 variables on each loan, for the purpose of this investigation I've taken the following variables: 
 - Term
 - LoanStatus
 - BorrowerRate
 - ProsperRating (Alpha)
 - LoanOriginalAmount
 - ProsperRating (numeric)
 - EmploymentStatus
 - DelinquenciesLast7Years
 - StatedMonthlyIncome
 - Recommendations
 - Investors
 - TotalProsperLoans

## Wrangling


# Univariate Exploration

### Loan status


- The majority of the loans in the data set are current loans. Past-due loans are classified into numerous categories based on the length of the payment delay.
- Another significant factor is completed loans, with defaulted loans constituting a minority.


    
![png](slide_deck._files/slide_deck._9_0.png)
    


# Bivariate Exploration

- There is insufficient information on part-time, retired, and unemployed borrowers for the job status variable to demonstrate how it interacts with term and Prosper rating factors. However, it is clear that word and Prosper rating interact in some way. There are proportionally more 60-month loans with B and C grades. Borrowers with HR ratings can only get loans for 36 months.


    
![png](slide_deck._files/slide_deck._12_0.png)
    


# Multivariate Exploration




    Current      56576
    Completed    38074
    Defaulted    17010
    Name: LoanStatus, dtype: int64



- Business and home improvement don't have nearly equivalent means at all, with the exception of auto.
- Business-related categories typically have more


    
![png](slide_deck._files/slide_deck._16_0.png)
    



      File "<ipython-input-8-ee5d943b0d7c>", line 1
        jupyter nbconvert slide_deck..ipynb \
                ^
    SyntaxError: invalid syntax
    

