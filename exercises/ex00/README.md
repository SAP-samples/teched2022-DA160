# Getting Started

## Get your guided experience trial system 

First you need to get your guided experience trial system of SAP Data Warehouse Cloud (mandatory).

1.	Click here.
<br>![](images/00_00_0010.png)

## Sample Business Scenario & Data Model Overview 

The sample data set for the session represents retail transactions from a number of outlet stores located in the United States. The transaction details include the store, the sold product, and the sales manager. In addition, the information on revenue, cost, discount, and profit is available for each transaction. 

The sales department is looking for a few analytics they need:

* **Year-over-Year Sales Comparison**<br>
They want to compare the current years’ company sales with the previous year.  

* **Sales Per Region**<br>
Due to an increase in the number of sales, the customer wants to understand how the different regions are  performing. Based on this visualization, the marketing team would identify the regions which are doing good as  well as the regions which need attention or better marketing campaigns  

* **Best Sales Representative**<br>
It is time for the company to reward the best Sales Representative for all the hard-work that has resulted in the  sales report. For this purpose, the company needs to have a visualization that shows revenue per sales  representative.  

The exercises will walk you through the steps using SAP Data Warehouse Cloud and SAP Analytics Cloud to answer those open questions, where the following tables are being used:  

| Table Name          | Description                           | Model Type          |
|:--------------------|:--------------------------------------|:--------------------|
| Sales Transactions  | Daily retail transactions per store   | Relational Dataset  |
| Store	              | Details per Store Outlet              | Dimension           | 
| Sales Manager       | Details on all Sales Manager          | Dimension           | 
| Product             | Details on the products being sold    | Dimension           | 


## Summary

Now that you have a guided experience trial system available and got a good understanding of the business scenario, we can start into the hands-on part.

Continue with [Exercise 01: First Log On (optional)](../ex1/README.md)
