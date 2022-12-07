# Criptocurrencies
From a dataset of cryptocurrencies, we are gping to analyze it to discover trends using unsupervised machine learning techniques. 

It was decided on unsupervised machine learning since we are looking for any groupins, trends or other information that can help present cryptocurrencies as a good investment for a company named "Accountability Accounting".

# Purpose
Accountability Accounting, a prominent investment bank, want us to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

# Cryptocurrencies Report

The data provided to perform the analysis is not ideal, so it will need to be processed to fit the machine learning models. Therefore, there is no known output has been decided to use unsupervised learning.

## 1. Preprocessing the Data for PCA
- After removing missing values, NaN values, duplicate rows, transforming datatypes, and dropping columns, we ended with the next dataset.

![image](https://user-images.githubusercontent.com/43974872/206102273-68a88f0f-5fa0-4048-813f-8f1cede73fa4.png)

- Then, we converted text features to variables with the get_dummies() method.

![image](https://user-images.githubusercontent.com/43974872/206102752-b77bd251-3e4b-4f42-9347-232e9047b70f.png)

- Finally, we standarize the data with StandardScaler() method.

## 2. Reducing Data Dimensions using PCA

## 3. Clustering Cryptocurrencies using k-means
## 4. Visualizing Cryptocurrencies Results
