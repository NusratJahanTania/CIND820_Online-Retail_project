# CIND820_Online-Retail_project

## Abstract:

The sale of goods and services over the internet is known as online retailing. In online retail, a business or individual sells retail products and services through online stores. Online retailers can increase their sales and profits faster than an offline shop as selling online offers the advantage of having an open store, twenty-four hours a day or seven days in a week. This advantage allows online retailers to expand their market globally or target an extremely focused groups. To gain profit in online retailing, it is important to set business strategies focusing customer buying attitude along with the sales’ trends. To achieve this, I chose an online retailing dataset to analyze the existing retailing trends and predict the future. There were number of analysis carried out previously by the researchers and they applied different data mining and machine learning algorithms to analyze the trends of customers’ buying and returning products from online retail stores around the world. They applied classification algorithms such as Naïve Bayes Algorithm, SMO Classifier, Lazy Learning, Bagging, Multi Boost AB and Dagging using different data mining tools such as Rapid Miner, WEKA, and KNIME which use the same platform (Java) and compared the results. In this project I performed exploratory analysis on ‘Online Retail’ data set and visualized different aspects of the dataset. I also conducted RFM analysis on the dataset followed by applying clustering and classification algorithms to segment the customers in different clusters and predict the future retailing trends of the customers. 

From this research work, I discovered following information and made decisions based on my findings:
1.	Analyze the dataset and visualize following aspects:

      •	Which country has made most of the transactions in between 01/12/2010 and 09/12/2011?

      •	Number of orders made by the customers during this time.

      •	Amount spent by the customers during this time.

      •	Monthly transactions during this time.

      •	Weekly transactions during this time.

      •	Hourly transactions during this time.

2.	Apply RFM model to analyze transaction pattern made by the customers in between 01/12/2010 and 09/12/2011
3.	Segment customers into different clusters of same characteristics using K-Means Clustering to understand which group made most recent and most frequent transactions and spent most amount in these transactions.
4.	Apply a classification model to predict the customer behavior in future. 


## Dataset used
https://archive.ics.uci.edu/ml/machine-learning-databases/00352/Online%20Retail.xlsx

## Related articles

[1] Cluster-based demand forecasting using Bayesian 
model averaging: An ensemble learning approach. Available at 
https://www.sciencedirect.com/science/article/pii/S2772662222000066?via%3Dihub

[2] Application of 
Ensemble Design for On-Line Retail E-Commerce for the Better Customer Response. 
Available at https://zenodo.org/record/804178#.Y_RKHnbMLIU

[3] Online Retail Customer Segmentation Analysis. Available at 
https://www.kaggle.com/code/lakshmi25npathi/online-retail-customer-segmentation-analysis/notebook

[4] Customer Segmentation – Combining RFM And Predictive Algorithms. Available at 
https://www.springml.com/blog/customer-segmentation-combining-rfm-and-predictive-algorithms

[5] Online Retail Dataset - Classification, Clustering and Regression. 
Available at https://www.codersarts.com/post/online-retail-dataset-classification-clustering-and-regression

[6] Online Retail - Data Analysis. Available at 
https://jovian.com/tusharg895/online-retail-data-analysis#C1



## Python Packages used
Pandas-profiling for EDA report: https://pypi.org/project/pandas-profiling/   
import pandas as pd  
import numpy as np  
from pandas_profiling import ProfileReport  
import seaborn as sns  
import matplotlib.pyplot as plt  
from numpy.lib.function_base import median
