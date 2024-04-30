# Bank-Marketing
In this project, we explore a direct marketing campaign dataset from a Portuguese banking business. The marketing compaigns were based on phone calls. It is common for the bank to contact the same client multiple times, in order to access if the customer want so sign up to a banking product such as term deposit.

The dataset bank_marketing.csv contains a cleaned-up sample of the orignial dataset publised to UCI Data Repository with additional columns. The response is a binary variabled named y, signifying if a client has subsribed to a term deport. There are 16 variables from the original data collection. Later it got enriched with additional 5 social and economic attributes. These 5 additional features are:

Data source: UCI Machine Learning Repository | Bank Marketing Data
Created by: Sérgio Moro (ISCTE-IUL), Paulo Cortez (Univ. Minho) and Paulo Rita (ISCTE-IUL) @ 2014

# Executive Summary

We analyzed data from a bank’s marketing campaigns to predict whether clients would subscribe to a term deposit. We employed various models, including logistic regression, ridge regression, random forest, and xgboost. Ridge regression exhibited the best performance with zero miss-classification, while others had miss-classification rates around 15%. The company can optimize its marketing campaigns by strategically determining the frequency of customer contacts, focusing on the most influential factors such as economic indicators and campaign-related features. For example, people who are older than 60 years old are more likely to get a subscription than younger, so contact them or focusing our campaign to this group like creating another benefits for them might increased the number of subscribers.

