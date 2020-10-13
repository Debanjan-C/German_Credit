# German Credit Risk Classification: Are you at Risk?

## Table of Contents
<pre>
Technical Notebook         : <a href=https://github.com/Debanjan-C/German_Credit/blob/main/Notebooks/Technical_Notebook.ipynb>Technical Notebook </a>
Code                       : <a href=https://github.com/Debanjan-C/German_Credit/blob/main/Notebooks/Code.ipynb>Code</a>
Data                       : <a href=https://github.com/Debanjan-C/German_Credit/blob/main/data/german_credit_data.csv>Data</a>
Data Web                   : <a href=https://www.kaggle.com/kabure/german-credit-data-with-risk>Data Web</a>
Powerpoint                 : <a href=https://github.com/Debanjan-C/German_Credit/tree/main/Presentation>Presentation</a>
Video                      : <a href=https://youtu.be/YMHCBM-dnzM>Presentation Video</a>
</pre>

## Overview
In this project, we are identiying the credit details of individuals in Germany and verifying their credit risks. I am passionate about this project, because I have heard about credit scores a lot in college days from parents and others. They all mentioned that with poor credit score, you cannot buy a car, house or anything. According to Investopedia, a poor credit score can make it harder to get car and home loans, and to qualify for credit card accounts." (Investopedia) Therefore, I wondered how would one know. I realized that we see a FICO credit score for our credit cards and all, but was not sure how I would be able to know the overall as the FICO credit score represents the score of that individual card. This data set is an intersting dataset where they have stored credit details of many individuals in Germany and considered many of the common factors like age, jobs, hosuing, savings account, checking account, etc. There are many interesting and common factors that are involved in this dataset. This dataset has 1,000 rows and 10 columns. In this project, I am a Data Scientist in Frankfurt, Germany working for a finance company. My role is to verify the credit details of individuals based on the information they provide like age, savings account amount, job, checkings account amount, housing information and many more. The objective is to take multiple features that play a role in determining an individuals credit risks and that column will be taken as the target for modelling. My role in the company is to verify whether the risk evalautions conducted by my co-workers in the company is correct or not. I intially conducted exploratory data analysis and data cleaning to fill in empty values with the term no account as null values represent that individuals do not have a savings or checkings account. Following that step, I conducted feature engineering to convert all letters and other non-numeric categorical values into numeric values. After those steps, I developed a logistics regression model where I split the data into test-train sets and tested my dataset. Following that, I used confusion matrix and found the accruacy, precision and recall values of each of the datasets. After those values were calculated, I decided to also compare the logistic regression training model with the decision tree training model and find the scores along with develop a confusion matrix. What also drove my curiousity is that I wanted to see if removing outliers from important columns or removing the null values in the initial dataset would affect the results of the logistics regression dataset. I realized that scores get better when using decision trees with max leaf nodes as 10 and removing outliers, but not when we remove the null values in intitial dataset. Removing outliers may not always be an option. Therefore, it would be more ideal to use decision tree as a solution. In the future, I would like to like to try increasing max leaf nodes in the decision tree model, try to removal the significant outliers in the entire dataset instead of two columns and check it and I would also like to see how an individuals job title or roles plays a role in credit risks and evaluating the accuracy.

## Business Goals
I am a Data Scientist in Frankfurt, Germany for a finance company where I am verifying the credit details of individuals based on the information they provide like their age, savings account amount, checking account amount, current credit amount, housing information, purchases, etc. Following that, the company evaluates the credit risk levels of each of the customers or individuals who come to us for service. If the risk columns says good then we understand that there is no risk and if it says bad then we have a risk. My role is to verify the accuracy of the risks and evaluate what could be a potential solution to help improve accuracy or provide any advice, so the company can let the user know when they are really under a serious risk and when they are not.

In order to predict the accuracy of the credit risk an individual posseses, I used logistic regression and decision trees to verify if the risk is correct or not. I compared the logistic regression and decision tree and realized that one is relatively better than the other one. I will be using supervised learning as we are given the labeled datasets and also will be developing test and training sets to check whether the overall regression model works. I realized that when we remove some of the outliers the percentage of the accuracy rises and when we ignore those who may not have a checkings or saings account then the accuracy percentage falls and seems to be more riskier.

## Motivation and Background
- "Poor credit can make it harder to get car and home loans, and to qualify for credit card accounts." (Investopedia) 
- "CompareCards by LendingTree conducted an online survey of more than 1,000 people and found that 37 percent either strongly or somewhat agreed with the statement, “I have no idea how my credit score is determined.”
- When I was in college, I have heard from many individuals like parents, other famile members, famile friends and many others that you should always be alert with your credti card, pay bills on time, pay your loans on time and accordingly protect your credit score. They also told me that with a poor credit score individuals can have a wide serious of trouble from buying a house, car, getting discounts, etc. 
  - That thought came into my mind and I was wondering how would one get an idea of their credit score. I always knew that credit card companies have a FICO score, but that is for that specific card and it may not be your overall score. Therefore, this was a project of interest to me. 

### Data
- Dataset: https://www.kaggle.com/kabure/german-credit-data-with-risk This dataset is in Kaggle where it contains all the features that will be used in evaluating whether a person has a credit risk or not and along with that it has a column that evaluates the risk. 
- We referred to this following dataset to gain an understanding of the features in more details: https://www.kaggle.com/uciml/german-credit The overall dataset was inspired by a dataset in the UCI repo: https://archive.ics.uci.edu/ml/datasets/Statlog+%28German+Credit+Data%29. 
- This dataset ontains information about individuals in Germany who provided information about their bank account details, jobs, etc and according to UCI, the initial dataset was published by Professor Hoffman in the University of Hamburg.
- Columns: Age, Sex, Job, Housing, Saving accounts, Checking account, Credit amount, Duration, Purpose, Risk
- The dataset has: **"100 rows and 10 columns."**


##  Contributor
<pre>
Contributer  : Debanjan Chowdhury
</pre>

##  Software Requirements - Packages used
<pre>
Languages    : Python
Tools/IDE    : Anaconda, Jupyter Notebook
Libraries    : pandas, matplotlib, seaborn, scikit learn
</pre>

<pre>
Last Updated : October 2020
</pre>

## Reference and contribution
<pre>
- Dataset: https://www.kaggle.com/kabure/german-credit-data-with-risk.
- Referred to: https://www.kaggle.com/uciml/german-credit
- Dataset inspired by: https://archive.ics.uci.edu/ml/datasets/Statlog+%28German+Credit+Data%29.
- https://www.cnbc.com/2019/01/04/about-4-in-10-americans-have-no-idea-how-credit-scores-are-determined.html
- https://www.investopedia.com/the-side-effects-of-bad-credit-4769783#:~:text=Poor%20credit%20can%20make%20it,%2C%20renter's%2C%20and%20homeowner's%20insurance.
</pre>
