# Online-Retail-Customer-Segmentation

 Online_Retail_Customer_Segmentation
 
Unsupervised-Machine-Learning-Capstone_Project

 Contributor :   Vibha kumari                                                         

Problem Description:
 In this project, your task is to identify major customer segments on a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

Data Description:
InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation. 
StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
 Description: Product (item) name. Nominal.
 Quantity: The quantities of each product (item) per transaction.Numeric.
 InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
 UnitPrice: Unit price. Numeric, Product price per unit in sterling.
 CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer. 
Country: Country name. Nominal, the name of the country where each customer resides.

The need of customer segmentation:

The differences in customers' behaviour, demographics, geographies, etc. help in classifying them in groups. Learning about different groups in the customer can help with following:
Target Marketing
Client understanding
Optimal product placement
Revenue growth.

Recency-Frequency-Monetary (RFM) model to determine customer value:

The RFM model is quite useful model in retail customer segmentation where only the data of customer transaction is available. RFM stands for the three dimensions:

Recency – How recently did the customer purchase?
Frequency – How often do they purchase?
Monetary Value – How much do they spend?
A combination of these three attributes can be defined to assign a quantitative value to customers. e.g. A customer who recently bought high value products and transacts regularly is a high value customer.


Approach taken

Data inspection
EDA
Data preparation
Create RFM model
Implementing various clustering Models and validating


Conclusion

Firstly we did clustering based on RFM analysis. We had 4 clusters/Segmentation of customers based on RFM score. Platinum customers=1263 ( less recency but high frequency and heavy spendings) Gold customers=1324 (good recency,frequncy and moentary) Silver customers=981(high recency, low frequency and low spendings) Bronz customers=770 (very high recency but very less frequency and spendings) Later we implemented the machine learning algorithms to cluster the customers.
Cluster 0 has low recency rate but high frequency and monetary. Cluster 0 conatins 1929 customers.
Cluster 1 has high recency rate but very low frequency and monetary . they are not frequent buyers and spends very less money than other customers as mean monetary value is very low.Thus generates less revnue to the retail business




