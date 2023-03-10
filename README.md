# Predict_Cutomer-Lifetime-Value_AnalyticsVidhya_JOB-A-THON_January2023

![Intro-IMAGE](https://user-images.githubusercontent.com/84449238/218296243-63154b6d-92dd-43b7-abd9-4302a420deaf.JPG)

**1) Problem Statement:-**

VahanBima is one of the leading insurance companies in India. It provides motor vehicle insurances at best prices with 24/7 claim settlement.  It offers different types of policies for  both personal and commercial vehicles. It has established its brand across different regions in India. 

Around 90% of the businesses today use personalized services. The company wants to launch different personalized experience programs for customers of VahanBima. The personalized experience can be dedicated resources for claim settlement, different kinds of services at doorstep, etc. Inorder to do so, they would like to segment the customers into different tiers based on their customer lifetime value (CLTV).

Inorder to do it, they would like to predict the customer lifetime value based on the activity and interaction of the customer with the platform. So, as a part of this challenge, your task at hand is to build a high performance and interpretable machine learning model to predict the CLTV based on the user and policy data.

**2) About the Dataset:-**

You are provided with the sample dataset of the company holding the information of customers and policy such as highest qualification of the user, total income earned by a customer in a year, employee status,  policy opted by the user, type of policy and so on and the target variable indicating the total customer lifetime value.

**2.1) Data Dictionary:-**

You are provided with 3 files - train.csv, test.csv and sample_submission.csv

**2.2) Train Set:-**

You are provided with around 90K records containing the attributes of the user and policy and the target variable cltv indicating the total customer lifetime value.

![IMG1](https://user-images.githubusercontent.com/84449238/213535976-d4899db5-1ad0-4f10-9fe3-0ce4244749d9.JPG)

**2.3) Test Set:-**

You are provided with around 60K records containing only the attributes of the user and policy and you need to predict the target variable cltv indicating the total customer lifetime value.

![IMG2](https://user-images.githubusercontent.com/84449238/213536032-087a2ecd-b7d5-4139-9120-e796ed6b9d4a.JPG)

**2.4) Submission File Format:-**

The solution file must contain the format similar to that of sample submission. sample_submission.csv contains 2 variables - id and cltv. 

![IMG3](https://user-images.githubusercontent.com/84449238/213536096-dc9343f0-7467-4256-9256-324816a75d52.JPG)

**3) Evaluation metric:-**

The evaluation metric for this hackathon would be r2_score.

**4) Public and Private Split:-**

Test data is further divided into Public (40%) and Private (60%) data.Your initial responses will be checked and scored on the Public data. The final rankings would be based on your private score which will be published once the competition is over.

## Summary

**a) Best Submission Score:-**

**1) Public Leaderboard :-** 0.1594171427

**2) Private Leaderboard :-** 0.1600135587

**b) Best Model:-** Ensemble Technique (Light Gradient Boosted Machine(LGBM) Regressor + Gradient Boosting Regressor + Multi Layer Perceptron Regression)

![Public_Leaderboard-AB](https://user-images.githubusercontent.com/84449238/218296657-43aaf06c-d8df-4843-b6e5-f6ddb35bd5c0.JPG)

![Private_Leaderboard-AB](https://user-images.githubusercontent.com/84449238/218296665-963338e5-8cc9-4770-ba45-79ea21a29b22.JPG)

**c) Competition Link:-** https://datahack.analyticsvidhya.com/contest/job-a-thon-january-2023/#LeaderBoard

**d) Rank Scored:-**

a) **25** out of **7416** registered participants (Public Leaderboard)

b) **161** out of **7416** registered participants (Private Leaderboard)
