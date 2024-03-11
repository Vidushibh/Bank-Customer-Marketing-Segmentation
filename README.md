**Bank Customer Marketing Segmentation using K-means and PCA**

## Objective
The objective of this project is to segment bank customers based on the following meta data using K-means clustering algorithm and Principal Component Analysis (PCA). By identifying distinct customer segments, banks can tailor their marketing strategies to better meet the needs of different customer groups, leading to more effective marketing campaigns and improved customer satisfaction.

## Metadata
CUSTID: Identification of Credit Card holder 
BALANCE: Balance amount left in customer's account to make purchases
BALANCE_FREQUENCY: How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)
PURCHASES: Amount of purchases made from account
ONEOFFPURCHASES: Maximum purchase amount done in one-go
INSTALLMENTS_PURCHASES: Amount of purchase done in installment
CASH_ADVANCE: Cash in advance given by the user
PURCHASES_FREQUENCY: How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)
ONEOFF_PURCHASES_FREQUENCY: How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased)
PURCHASES_INSTALLMENTS_FREQUENCY: How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done)
CASH_ADVANCE_FREQUENCY: How frequently the cash in advance being paid
CASH_ADVANCE_TRX: Number of Transactions made with "Cash in Advance"
PURCHASES_TRX: Number of purchase transactions made
CREDIT_LIMIT: Limit of Credit Card for user
PAYMENTS: Amount of Payment done by user
MINIMUM_PAYMENTS: Minimum amount of payments made by user  
PRC_FULL_PAYMENT: Percent of full payment paid by user
ENURE: Tenure of credit card service for user

## Data Source
The dataset used in this project is obtained from Kaggle : https://www.kaggle.com/arjunbhasin2013/ccdata

## Tech Stack
- Python Libraries:
  - pandas
  - scikit-learn
  - matplotlib
  - seaborn
- ML Techniques :
  - KMeans
  - PCA

## References
  - https://en.wikipedia.org/wiki/Elbow_method_(clustering)
  - https://www.geeksforgeeks.org/elbow-method-for-optimal-value-of-k-in-kmeans/
