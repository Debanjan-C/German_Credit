# Data_602 
# Debanjan Chowdhury

# Predicting Insurance Premiuim Cost for ABC Inc.

## Repository Navigation
<pre>
Technical Notebook         : <>Technical Notebook </a>
Code                       : <></a>

</pre>

## Overview
Project Title: German Credit Risk Classification: Are you at Risk?

This is a project where we are identiying the credit details of individuals in Germany and verifying their credit risks. I am passionate about this project, because I have heard about credit scores a lot in college days from parents and others. They all mentioned that with poor great credit score, you cannot buy a car, buy a house or anything. According to Investopedia, Poor credit can make it harder to get car and home loans, and to qualify for credit card accounts." (Investopedia) Therefore, I wondered how would one know. When I got my credit cards and all, I realized that we see a FICO credit score for our individual cards and all. However, I was not sure how I would be able to know the overall. This data set is an intersting dataset where they have stored credit details of individuals in Germany considering many of the common factors like age, jobs, hosuing, savings account, checking account, etc. There are many interesting and common factors that are involved in this dataset.  In this project, I am a Data Scientist in Frankfurt who is working for a I am a Data Scientist in Frankfurt for a finance company where I am verifying individuals credit details based on the information they provide like age, savings account amount, job , checkings amount amount, housing information and many more. Our dataset has about 10 columns and 1,000 rows with mostly categorical and classification datas. The objective is to take multiple features that play a role in determining an individuals credit risks and in the target section. we have the binary classifciation data where it tells us if we are in the risk zone or now. My role in the company as a data scientist is to verify whether the risk evalautions made by co-workers in the company is correct or not. I intially do exploratory data analysis and data cleaning to fill in empty values with the term no account as null values represent that individuals do not have a savings or checkings account. Next, I conductedd feature engineering to convert all letters and other non-numeric categorical values into numeric values as models would use all numeric values After those steps, I developed a logistics regression model where I split the data into test-train sets and tested my dataset. Following that, I used a precision matrix and found the accruacy, precision and recall values of each of the datasets. After that, I decided to also compare the logistic regression training model with the decision tree training model and find the accuracy and other scores along with develop a confusion matrix. What also drove my curiousity is that I wanted to see if removing outliers from important columns or removing the null values in the initial dataset would affect the results of the logistics regression dataset. 

## Business Goal 
I am a Data Scientist in Frankfurt for a finance company where I am verifying individuals credit detailss based on the information they provide me like their age, bank savings about details, checking account details, current credit amount, housing information, the purpose of their credit details, etc. Following that, it is evaluated by the company about the risk levels of whether it is considered good or bad. My role is to verify the accuracy of the risks and evaluate what could be a potential solution to help improve accuracy or provide any advice, so the company can let the user know when they are really under a serious risk and when they are not.

In order to predict the accuracy of the credit risk an individual posseses, I used logistic regression and decision trees to verify if the risk is correct or not. I compared the logistic regressiona nd decision tree and realized taht one is relatively better than the other one. I will be using supervised learning as we are given the labeled datasets and also will be developing test and training sets to check whether the overall regression model works. I realized that when we remove some of the outliers the percentage of the accuracy rises and when we ignore those who may not have a checkings or saings account then the accuracy percentage falls and seems to be more riskier.

## Motivation and Background
- "Poor credit can make it harder to get car and home loans, and to qualify for credit card accounts." (Investopedia) 
- "CompareCards by LendingTree conducted an online survey of more than 1,000 people and found that 37 percent either strongly or somewhat agreed with the statement, “I have no idea how my credit score is determined.”
- When I was in college, I have heard from many individuals like parents, other famile members, famile friends and many others that you should always be alert with your credti card, pay bills on time, pay your loans on time and accordingly protect your credit score. They also told me that with a poor credit score individuals can have a wide serious of trouble from 

### Data
Dataset: https://www.kaggle.com/teertha/ushealthinsurancedataset. This Dataset in Kaggle was used to predict the premium prices of individuals throughout the U.S.

Columns: 
- age, 
- gender, 
- children, 
- BMI (Body Mass Index) 
- smoker (checks if individual smokes or not) 
- charges. 
- (Region field was dropped) Therefore, dataset had **6 columns and 1338 rows**

## Challenges & Limitations
I feel one of the challenge was the outliers part there were so many and it seemed that due to the fact that we had multiple x values, it was difficult to figure out where we can remove the outliers. If we look at the outliers with respect to x1 then I felt that we may get rid of some core data in another x value. Therefore, that was somthing I had difficulty with.

##  Conclusions
I feel that this model does evaluate we have a positive linear relationship when all of the x-values are taken into the model. However, I also feel that our residual plot and regression plots were not the best to evaluate the trends, but that is a plan to improve in the long run. Possibly, being able to evaluate which outliers or leverage points to remove, they may look relatively better. In general, medical insurance companies could look for more data into family medical history and other details. Those other factors could be taken into consideration next time. My R-squared value is 0.746 or 74.6% reliability of the x-variable which is somewhat reliable. The closer the value is to 1 the better.

<pre>
Contributer  : Debanjan Chowdhury
</pre>

##  Software Requirements
<pre>
Languages    : Python
Tools/IDE    : Anaconda, Jupyter Notebook
Libraries    : pandas, matplotlib, seaborn, statsmodel api, scikit learn
</pre>

<pre>
Last Updated : September 2020
</pre>

## References and contributions
<pre>
- Dataset: https://www.kaggle.com/kabure/german-credit-data-with-risk.
- Referred to: https://www.kaggle.com/uciml/german-credit
- Dataset inspired by: https://archive.ics.uci.edu/ml/datasets/Statlog+%28German+Credit+Data%29.
- https://www.cnbc.com/2019/01/04/about-4-in-10-americans-have-no-idea-how-credit-scores-are-determined.html
- https://www.investopedia.com/the-side-effects-of-bad-credit-4769783#:~:text=Poor%20credit%20can%20make%20it,%2C%20renter's%2C%20and%20homeowner's%20insurance.
</pre>
