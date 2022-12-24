# Logistic-Regression-Prediction-of-Canada-Election
Prediction of Individual Characteristic Shape Voting Preference for Liberal Party by Logistic Regression

   - Logistic-Regression-Prediction-of-Canada-Election.Rmd: Original code of our report  
   - Logistic-Regression-Prediction-of-Canada-Election.pdf: Final report    
   - ces2019-phone_clean.csv: Raw data  
   - gss_clean.csv: Raw data  
   
## Introduction

This report is a study on the prediction of the outcome of the election accurately. Many companies, government organizations, and agents built-up models, trying to find the relationship between voters' preference and other factors.

We used the survey data about people's preferences of voting and their characteristics to build our analysis. Then we use the census data from 2019 to complete the prediction.

## Data Sets

In the research, the first dataset we refer to is the GSS (General Social Survey: Families), conducted in 2017. The data was collected by using a computer-assisted telephone interview, with an overall response rate of 52.4%. The total number of usable observations is 20602 households, and the dataset includes essential variables, such as social-demographic information (age, education, sex), income level, etc.

The second dataset we use is the CES (Canadian Election Study) conducted in 2019. The data were collected with telephone interviews, with 4021 Canadian citizens aged over 18 completing the survey. There are 278 variables in the data, including sex, phone type, interest in the party, living region, and so on. 

## Remarks

1.	When holding other variables fixed, older voters tend to vote for Liberal Party. Also, when voters grow older, they are more likely to vote for the Conservative Party when keeping other variables unchanged. Both of the results are of statistical significance. 

2.	When holding other variables fixed, we cannot find a difference in the probability of voting for the Liberal Party between males and females. However, we found a statistically significant difference between males and females when voting for Conservative Party. On average, male voters have a higher probability of voting for the Conservative Party.

3.	When holding other variables fixed, voters of lower educational level tend not to vote for Liberal Party, compared with those who possess degrees above bachelor. In contrast, when holding other variables fixed, voters of lower educational level has increased odds of voting for the Conservative Party with statistical significance, compared with the voters who possess degrees above bachelor. 

4.	When holding other variables fixed, voters living in different regions (provinces) indeed have a significantly different likelihood of voting for the Liberal Party. Similarly, voters residing in the various areas present quite different odds of voting for the Conservative Party. 

5. Based on the logistic regression model, we further applied the post-stratification method to predict the probability of each party's winning the future election. The likelihood of the Liberal Party's winning the vote is 22.20%, the possibility for Conservative Party is 25.69%, while the probability for New Democrat is 9.94%. Therefore, among these three parties who possess the most incredible popularity in the past few years, The Conservative Party has the highest probability of winning the election in 2025. 
