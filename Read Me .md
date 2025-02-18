#  Financial Risk Assessment Project 
## Introduction
the risk assessment is a crucial process in detecting potential risks , it envolves evaluating of Adverse outcums and their affect on indivisuals and organizations.
The Financial risk assessment helps in Quantifaying risks,ensuring an informed decison Making.

In this project i analyzed Key Financial Variabels such as 'Income' , Loan Amount , Age , Gender ..etc
To 
- assess The factors cotuributing to Financial risks 
- The indecators for approving a lone 
- Helping in making risk_aware decisons.

#

## Tool I Used :
- Python :  The primary tool and i used the following libiraries:
- Pandas : For Data manipulation and Cleaning
- numpy : For Data processing and numerical computations
- matplotlib & Seaborn : for Visualization 
- Jupyter Notebook 
- Visual Studio code 
- Git & Github
#

# The Analysis :
 The analysis Foucesses on Uncovering patterns and potential predictors of finincial Instability.
### Data Cleaning :
after the Eda process i found null values in various columns in the data frame like (loan amount, credit score ,age)
and the cleaning process also envolved Chainging Data Types and Cheacking for Outliers 
and also Processing The data and adding column like Age Groups Based on the Column Age.
# THE Questions :
-  First the disturbution of variabels 
-  how does the income varies by difrrent age groups 
-  Relationship Between Credit Score And Loan Amount
-  Geographic Infleuence on assessment
-  For Low And high risk countries what are the elements that affect the assessment process
-  is there is a relationship between education and risk assessment
-  Do correlation on several metrics .
#

# Insights i Found :

- The distribution of risk ratings shows that low ratings are the most common, with over 8,000 assessments, while high-risk ratings are much less frequent, with only 1,900 assessments.  
- The loan amount distribution is very stable, with loans ranging between 20,000 and 40,000.  
- The credit score also has a stable distribution, varying between 675 and 750.  
- Yearly income varies between 50,000 and 90,000.  
- In the dataset, individuals aged between 25 and 45 have the highest overall income.  
- Males tend to have more low-risk ratings, and correspondingly, males also have slightly higher overall income.  
- The higher the credit score, the higher the loan amount one can obtain.  
- Some countries, like Korea and Andorra, have very low risk ratings. This may be due to factors such as a strong economy, low population, and government easing policies.  
- It is noticeable that these low-risk rating countries tend to have high credit scores.  
- On the other hand, some countries, like Chile, have high-risk ratings. Possible reasons include:  
    - High debt levels  
    - Political instability  
    - Inflation  
- Educational level also affects risk ratings. Ph.D. holders have the highest number of low-risk ratings and are more likely to get loan approvals, followed by bachelor’s degree holders.  
- Credit score and loan amount have the highest correlation.  
#


## main plots
!['Risk count'](plots/rsisk-count.png)
#
!['Loan risk](plots/loan_risk.png)
#
!['Gender risk'](plots/gender_risk.png)
#
!['countries](plots/Countries.png)
#
!['Low countries'](plots/low_countries.png)
#
!['Correlation](plots/corr.png)

#
#  Conclusions :
In summary, the analysis highlights key factors influencing financial risk, including credit scores, loan amounts, and educational levels. Low-risk countries like Korea and Andorra exhibit strong economies and high credit scores, while high-risk regions face challenges such as debt and political instability. Additionally, age, gender, and income levels reveal trends in loan approval and risk assessment, with Ph.D. holders and high credit scores being strong indicators of low financial risk.

