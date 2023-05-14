# Online-Retail-Customer-Segmentation
![image](https://github.com/Pradeep1023/Online-Retail-Customer-Segmentation/assets/112772717/4f377a7b-0d60-40b7-af51-d36ff257cc67)

![image](https://github.com/Pradeep1023/Online-Retail-Customer-Segmentation/assets/112772717/c4bb3234-d5ec-4d0c-a988-0288c765ea8b)

**Table of Content**

Introduction

Problem Statement

Data Description

Steps Involved

Algorithms Used

Conclusion

![image](https://github.com/Pradeep1023/Online-Retail-Customer-Segmentation/assets/112772717/d65e8c7e-4bcf-477a-98d2-42dd11fcb0a1)

**Introduction**

Customer segmentation in online stores is a vital strategy that involves dividing a diverse customer base into distinct groups based on their shared characteristics, behaviors, and preferences. With the increasing popularity of online shopping, businesses strive to better understand their customers and tailor their marketing efforts accordingly. Through effective customer segmentation, online stores can target specific groups with personalized marketing campaigns, product recommendations, and pricing strategies. By analyzing customer data such as demographics, purchasing behavior, browsing patterns, and past interactions, businesses gain valuable insights into the unique needs and preferences of different customer segments. 

![image](https://github.com/Pradeep1023/Online-Retail-Customer-Segmentation/assets/112772717/0653c4c5-0e93-4759-9c7d-526bd1261523)

**Problem Statement**

The company mainly sells unique all occasion gifts. Many customers of the company are wholesalers. In this project our task is to identify major customer segments on a transnational data set which contains all the transactions occurring between 01-12-2010 and 09-12-2011 for a UK based and registered non store online retail.

![image](https://github.com/Pradeep1023/Online-Retail-Customer-Segmentation/assets/112772717/6a8ec085-b7b5-474a-948f-979d1e6b7684)

**Data Description**

* InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
* StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
* Description: Product (item) name. Nominal.
* Quantity: The quantities of each product (item) per transaction. Numeric.
* InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
* UnitPrice: Unit price. Numeric, Product price per unit in sterling.
* CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
* Country: Country name. Nominal, the name of the country where each customer resides.

![image](https://github.com/Pradeep1023/Online-Retail-Customer-Segmentation/assets/112772717/4273a4b4-52b0-49e2-ae5a-9e92ba76f614)

**Steps Involved**

Data Preprocessing: Handeled null values, removed duplicated values, out of total orders 2.2% were cancelled so removed cancelled orders.

Feature Extraction: Extracted features day name, month name, year, and hour from Invoice Date.

Feature Engineering: Performed feature engineering, created new feature 'Total Amount' by multiplying Quantity and Unit Price. Created new attributes, including Recency , Frequency , Monetary , and RFM scores to learn more about the customer characteristics.

Exploaratory Data Analysis: Performed Univariate, Bivariate, and Multivariate analysis with various graphs and plots to better understand the patterns and distribution of features.

Implemented clustering algorithms

Plotted Elbow plot, calculated average silhouette score, and examine the Dendrogram produced by Hierarchical Clustering.

![image](https://github.com/Pradeep1023/Online-Retail-Customer-Segmentation/assets/112772717/d759a0c4-24d3-466b-87fc-5a5ecaf00032)

**Algorethims used**

K-Means Clustering

Hierarchical Clustering

![image](https://github.com/Pradeep1023/Online-Retail-Customer-Segmentation/assets/112772717/10dd9ad3-cb55-4fa6-986c-17b15866d6fc)

**Conclusion**

* Out of the total orders 2.2% order were cancelled.
* In all the products, top selling products were 'White hanging heart t-light holder’, ‘Regency cakestand 3 tier’, ‘Jumbo bag red retrospot’ and ‘Assorted color bird ornament’.
* Most number of orders placed by customer is on Thursday and least number of orders were placed on Friday.
* The highest percentage of orders were placed in November, while the lowest percentage were placed in February.
* The majority of orders are placed in the afternoon, while very few are placed between 8 PM and 7 AM.
* After looking at the Elbow plot, Dendrogram, and Silhouette score, we realised number of clusters can be taken as two or three.
* Three clusters were created using the two clustering techniques Kmeans and Agglomerative clustering, and the customers within these clusters are clearly divided.

![image](https://github.com/Pradeep1023/Online-Retail-Customer-Segmentation/assets/112772717/8d26d264-0618-48be-9fbd-7d86de8beb1e)
