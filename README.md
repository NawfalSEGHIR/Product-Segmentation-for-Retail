# Product-Segmentation-for-Retail

#### How to use Python and ABC classification for product classification in a Warehouse. 
#### Many Thanks to Sami SACI, my inspiration for this project. please visit his Github profil for more insightful Supply chain projects: https://github.com/samirsaci 
#### Data for this project are downloadable from Kaggle : https://www.kaggle.com/c/m5-forecasting-accuracy/data


In this project, we will try to do a product segmentation using Python. We will study our products sales in term of:

•	Contribution to our total Turnover using ABC Analysis
•	Demand stability i.e Variability

1.	Problem Statement 

Let’s assume you are an Operational Director of a Distribution Center (DC) that delivers 10 Hypermarkets.

2.	Scope Analysis

This analysis will be based on the M5 Forecasting dataset of Walmart stores sales records: 
https://www.kaggle.com/c/m5-forecasting-accuracy/data

We suppose that we only have the first-year data (d_1 to d_365):

•	10 stores in 3 states (USA)
•	1,878 unique SKU
•	3 categories and 7 departments (sub-category)

3.	Products Rotation

We classify our items by sales: 

•	Very fast Movers are the top 5% most selling products (Class A)
•	Fast Movers are the following 15% (Class B)
•	Slow movers are the remaining 80% (Class C)

This classification will impact our: 

•	Warehouse Layout
•	Picking Process

4.	Demand Variability

Now we should study our customer’s Demand trough:

•	Average sales: µ
•	Standard Deviation: σ
•	Coefficient of Variation: CV = σ/ µ

For SKUs with a high value of CV, you may face unstable customer demand (Peaks of Demand or Volatility) that would lead to workload peaks, forecasting complexity and stock-outs.

https://exceltable.com/en/analyses-reports/abc-xyz-analysis-in-excel

Shapiro-Wilks Normality Test:

The Shapiro-Wilks test for normality is one of three general normality tests designed to detect all departures from normality. It is comparable in power to the other two tests. The test rejects the hypothesis of normality when the p-value is less than or equal to 0.05.
