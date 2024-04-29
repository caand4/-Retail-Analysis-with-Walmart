# Retail Analysis with Walmart

## Business Scenario
Walmart is one of the biggest companies in the US with many stores across the country. One very vital aspect of Walmart’s success is strategic planning and data analysis. The company has recently run into a Machine Learning algorithm error that has caused challenges due to unforeseen demands. As such, Walmart wants to acquire a model that would accurately predict future sales of the company. 
Walmart considers that there will be factors impacting sales such as holidays or non-holidays, CPI, unemployment index, fuels price and temperature. The main holidays that affect weekly sales are Superbowl, Labour Day, Thanksgiving and Christmas. The company has collected data from 45 stores within the years of 2010-2012. 
The goal of this analysis is to explore how weekly sales have been affected and to build a prediction model to forecast demand.

## Objectives

- Which store has maximum sales
- Which store has maximum standard deviation i.e., the sales vary a lot. Also, find out the coefficient of mean to standard deviation
- Which store/s has good quarterly growth rate in Q3’2012
- Some holidays have a negative impact on sales. Find out holidays which have higher sales than the mean sales in non-holiday season for all stores together
- Provide a monthly and semester view of sales in units and give insights
- Build a prediction model to forecast demands

## Data Summary

![image](https://github.com/caand4/-Retail-Analysis-with-Walmart/assets/80293132/301eeccd-15fa-43ed-83c8-aaf7157f9c17)

## Data Exploration 
#### Objective I
![image](https://github.com/caand4/-Retail-Analysis-with-Walmart/assets/80293132/223bc98b-2d9c-4277-a52c-609a079b1d71)
![image](https://github.com/caand4/-Retail-Analysis-with-Walmart/assets/80293132/24899fb0-9d87-4887-8934-4800d20f95d9)
#### Objective II

![image](https://github.com/caand4/-Retail-Analysis-with-Walmart/assets/80293132/ef9b39a9-6394-4e84-b938-3cacc42aa5f1)

## Data Manipulation
#### Objective III
![image](https://github.com/caand4/-Retail-Analysis-with-Walmart/assets/80293132/1e8b325a-7138-405a-8e88-eb6b4754b6f1)

![image](https://github.com/caand4/-Retail-Analysis-with-Walmart/assets/80293132/a3b53c24-5266-4afd-a714-ec2ca609c2ed)

![image](https://github.com/caand4/-Retail-Analysis-with-Walmart/assets/80293132/72314acf-8f5a-4d8a-8be7-e2b828198ae4)

##### Objective IV
![image](https://github.com/caand4/-Retail-Analysis-with-Walmart/assets/80293132/7b16d49e-0d04-4420-86f6-f17083479ce7)
##### Objective V
![image](https://github.com/caand4/-Retail-Analysis-with-Walmart/assets/80293132/7cc84bd6-2d01-417f-8fab-0ed43bb1b514)
![image](https://github.com/caand4/-Retail-Analysis-with-Walmart/assets/80293132/1cdc2620-3848-4b55-a750-2a3df2c60b93)
![image](https://github.com/caand4/-Retail-Analysis-with-Walmart/assets/80293132/7ebe0616-3d31-4eb2-88b3-bdfd76a67123)
![image](https://github.com/caand4/-Retail-Analysis-with-Walmart/assets/80293132/60cce063-5d11-457a-af7c-2e864d4dff2e)

#### Multiple Linear Regression!

![image](https://github.com/caand4/-Retail-Analysis-with-Walmart/assets/80293132/a310de6c-eea5-44b4-a012-579d049dec3b)

#### Statistical Analysis:
The problem statement can be addressed using linear regressionVIF Method!

![image](https://github.com/caand4/-Retail-Analysis-with-Walmart/assets/80293132/593823b5-4c7d-4193-b364-cf9369e391ec)

#### Statistical Analysis:
Significance Method: Model 1
![image](https://github.com/caand4/-Retail-Analysis-with-Walmart/assets/80293132/42f1a369-41bb-4f92-a196-c3710a8cc050)

![image](https://github.com/caand4/-Retail-Analysis-with-Walmart/assets/80293132/0a7445aa-262a-4a83-85ab-0ca486014d06)
![image](https://github.com/caand4/-Retail-Analysis-with-Walmart/assets/80293132/3b232584-1b37-48e1-93ba-ea265d6b725f)

#### Dwtest is used to check for autocorrelation among residual errors. 
![image](https://github.com/caand4/-Retail-Analysis-with-Walmart/assets/80293132/8a4e5619-75c3-4b76-a767-6c3658348d5a)

#### Statistical Analysis:
Significance Method: Model 2 
![image](https://github.com/caand4/-Retail-Analysis-with-Walmart/assets/80293132/d5729aea-547c-436d-9e44-257f9746bdab)
#### Variance Inflation Factor Analysis
![image](https://github.com/caand4/-Retail-Analysis-with-Walmart/assets/80293132/f511562e-c91a-4d5c-884e-68d29bca72bd)
![image](https://github.com/caand4/-Retail-Analysis-with-Walmart/assets/80293132/31b30eb0-7861-44c1-8036-1d1b3b094dc2)
![image](https://github.com/caand4/-Retail-Analysis-with-Walmart/assets/80293132/2ded528c-5ca8-416b-81db-e746cbd0880e)
#### Dwtest is used to check for autocorrelation among residual errors. 
![image](https://github.com/caand4/-Retail-Analysis-with-Walmart/assets/80293132/e6d68f31-12e6-4d99-98f7-b34380741f40)
#### Step Method: Model 3 
![image](https://github.com/caand4/-Retail-Analysis-with-Walmart/assets/80293132/098c3f9a-c466-4515-afa6-3e873429557b)
![image](https://github.com/caand4/-Retail-Analysis-with-Walmart/assets/80293132/b1d45f9e-8847-4be7-b04a-3b710512e46e)
![image](https://github.com/caand4/-Retail-Analysis-with-Walmart/assets/80293132/f4461b2e-3e55-4849-91c9-6c1a68a0f5b7)
#### Dwtest is used to check for autocorrelation among residual errors. 
![image](https://github.com/caand4/-Retail-Analysis-with-Walmart/assets/80293132/8d6ea3e5-a032-437b-8937-88451f40a2bb)
#### Comparison of Models:
![image](https://github.com/caand4/-Retail-Analysis-with-Walmart/assets/80293132/93292ee3-cd55-4ade-bc63-dcaaf735b65f)

## Conclusion!
The aim of this analysis was to build a model to forecast demands. In order to achieve the aim, data was analyzed using a statistical approach. Weekly sales of the 45 Walmart stores have been thoroughly analyzed, thus the following can be concluded:
- Store 20 has the maximum weekly sales
- Store 14 sales vary the most
- In Quarter 3, Store 7 has the highest growth rate from Q2->Q3’2012 & Store 44 highest growth rate from the previous year 2011 to 2012 of the same quarter, Q3.
- The holiday that dominates for highest weekly sales is Thanksgiving.
- The best prediction model to forecast demand is 
#weeklysales=-233190-2769temp1+9156cpi1












































