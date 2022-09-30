# Exercise 3 - Data Layer - Prepare Your Data

Before we are going to start with our first exercise in creating a table and creating our first model, lets clarify the
different asset types that you can create in SAP Data Warehouse Cloud.
When you launch the Data Builder from the menu, you will be presented with this screen:
<br>![](images/00_00_0031.png)

So, let’s now look at the different asset types:
- Table: Here you basically define a new table from scratch, and you configure each field of the table and
you do have the ability then to upload data to this table later on.</p>
- Graphical View: In the Graphical View you can leverage Tables and Views to the create new Views
using a visual interface.</p>
- SQL View: In the SQL View you can leverage Tables and Views to the create new Views by using SQL
directly.</p>
- Entity Relationship Model: Here you define the relationships between Tables or Views, which then are
being leveraged when you create a new View based on the Tables or Views.</p>
- Data Flow: Here you can define data transformations and leverage the option to load data from a source
system into SAP Data Warehouse Cloud.</p>

In this section we will start creating the tables for our sample models and then upload the raw data to those
tables. In the first part of this overall section, we will look at the sample model and which tables we will need. In
the second part we will then create those tables in SAP Data Warehouse Cloud and finally in the third part, we
will upload the raw data to those newly created tables, and we will also setup a hierarchy as part of the tables.

In the next steps we will setup a relatively simple data model and we will start by creating the tables first and
then upload the information for each table in form of CSV Files

In the next steps we will start to create the tables in SAP Data Warehouse Cloud.

1. Log On to your SAP Data Warehouse Cloud tenant.</p>
2. Select the menu option Data Builder on the left-hand side.</p>
3. In case you are being asked, select your previously created Space – ANA161_XX.</p>
<br>![](images/00_00_0031.png)
4. Select the option New Table</p>
<br>![](images/00_00_0032.png)
5. You are being presented with the details to create a new table.
6. Enter the following details:<br><ul><li>Business Name - Sales Transactions</li><li>Technical Name - Sales Transactions</li><li>Type - Relational Dataset
<br>

7. We also can provide already as part of the table, some business description and Tags, which then will be
used as part of the Business Catalogue.

8. Enter the following details for the Business Purpose:<br><ul><li>Description - This is the table for the Sales Transactions</li><li>Tags - Sales transaction, Revenue, transactions<br>

:bulb: **Tip:** </p>
Please note, that when entering the <strong>Tags</strong>, you have to enter each tag individually for now and you can’t enter
multiple tags separated by comma right now.

9. Scroll down to the area Columns (you can also use the tabs in the page header for navigation). Here you
define now the structure of the table by adding the individual columns.
<br>![](images/00_00_0032.png)

10. Use the “+” sign in the top right corner of the Columns area to start the process of creating your first table
column
<br>![](images/00_00_0033.png)

11. You now need to enter a Business Name, a Technical Name, and you need to configure the Data Type
12. For the first column, enter the following details:<br><ul><li>Business - Name Transaction ID</li><li>Technical Name - Transaction_ID</li><li>Data Type - Integer64<br>

:bulb: **Tip:** </p>
Please note, that you can change the <strong>Data Type</strong> simply by clicking on the item in the Data Type column.

13. After you entered the details for the first column, please enter the following additional columns:
  
| Business Name:      | Technical Name:                       | Data Type:          |
|:--------------------|:--------------------------------------|:--------------------|
| Transaction ID      | Transaction_ID                        | Integer64           |
| Transaction Date    | Transaction_Date                      | Date                | 
| Store ID            | Store_ID                              | String (6)          | 
| Product ID          | Product_ID                            | String (4)          | 
| Sales Manager ID    | Sales_Manager_ID                      | String (4)          | 
| Profit              | Profit                                | Decimal(15,2)       | 
| Discount            | Discount                              | Decimal(15,2)       | 
| Revenue             | Revenue                               | Decimal(15,2)       | 
| Cost                | Cost                                  | Decimal(15,2)       |   
  
14. After you entered all columns for the table, ensure you enable the Key Column option for the column
Transaction ID.
<br>![](images/00_00_0034png) UPLOAD 
  
15. Now use the Save option in the General menu.
<br>![](images/00_00_0035ng) UPLOAD 
  
16. On the first time you save the table, you will be asked to confirm the name and technical name.
17. Click Save.
18. After you saved the changes, you also have to deploy the table, so that we can later on upload data to the table.
19. Use the Deploy option from the General menu  
<br>![](images/00_00_0036g) UPLOAD   
  
20. We configured, saved, and deployed our first table.
21. Now use the Back option in top menu or as alternative you can click on your Space name to navigate back
to the list of tables. 
<br>![](images/00_00_0037) UPLOAD   

22. You are back at the home screen of the Data Builder and you should see your table in the list of objects.
23. Use the option New Table.
24. Enter the following details:<br><ul><li>Business Name - Store</li><li>Technical Name - Store</li><li>Type - Dimension<br>
<br>

25. Navigate to the Attributes area.<br>


26. You will notice, based on the Type Dimension, we now have two additional options for each Column:
Semantic Type and Label Column.
The Label Column allows you to specify a column from the table to be used as Label. For example, you
could have a Product ID and a Product Description in the table and use the Product Description column as
Label for the Product ID.
The Semantic Type option provides you with several option to choose from, so that you can configure an
additional context for the column, such as the option to configure the column as a Currency column or a
language column.

27. Use the “+ sign to create new attributes.
  
28. Enter the following Attributes for the table:  
  
| Business Name:      | Technical Name:                       | Data Type:          | Semantic Type       | Label Column   |
|:--------------------|:--------------------------------------|:--------------------|:--------------------|:---------------|
| Store ID            | Store_ID                              | String (6)          | None                | Store_Name     |
| Store Name          | Store_Name                            | String (30)         | Text                |
| Store City          | Store_City                            | String (20)         | 
| State ID            | State_ID                              | String (2)          | 
| State Name          | State_Name                            | String(30)          | 
| Country             | Country                               | String(30)          | 
| Latitude            | Latitude                              | Decimal(15,8)       | 
| Longitude           | Longitude                             | Decimal(15,8)       | 
    
:bulb: **Tip:** </p>
Please note, that you can only select the Store Name for the <strong>Label Column</strong> after you entered the details for
the Store Name into the Attributes.
  
29. After you entered all columns for the table, ensure you enable the Key Column option for the column Store ID.
30. Click Save in the General menu.
31. You will be asked to confirm the Business Name as well as the Technical Name.
32. Click Save.
33. Click Deploy in the General Menu.
34. Use the Back option in top menu or as alternative you can click on your Space name to navigate back to the home screen of the Data Builder.
35. Use the option New Table.
36. Enter the following details:<br><ul><li>Business Name - Product</li><li>Technical Name - Product</li><li>Type - Dimension<br>
<br>  
  
37. Navigate to the Attributes for the table.
38. Enter the following Attributes for the table:
 
| Business Name:        | Technical Name:                       | Data Type:          | Semantic Type       | Label Column          |
|:----------------------|:--------------------------------------|:--------------------|:--------------------|:----------------------|
| Product ID            | Product_ID                            | String (4)          | None                | Product Name          |
| Product Name          | Product_Name                          | String (30)         | Text                |                       |
| Product Category ID   | Product_Category_ID                   | String (4)          | None                | Product Category Name |
| Product Category Name | Product_Category_Name                 | String (30)         | Text                |                       |  
  
39. After you entered all columns for the table, ensure you enable the Key Column option for the column Product ID.
40. Click Save in the General menu.
41. You will be asked to confirm the Business Name as well as the Technical Name.
42. Click Save.
43. Click Deploy in the General Menu.
44. Use the Back option in top menu or as alternative you can click on your Space name to navigate back to the home screen of the Data Builder.
45. Enter the following details:<br><ul><li>Business Name - Sales Manager</li><li>Technical Name - Sales_Manager</li><li>Type - Dimension<br>
<br>  
46. Navigate to the Attributes for the table.<br>
47. Enter the following Attributes for the table:

| Business Name:        | Technical Name:                       | Data Type:          | Semantic Type       | Label Column          |
|:----------------------|:--------------------------------------|:--------------------|:--------------------|:----------------------|
| Sales Manager ID      | Sales_Manager_ID                      | String (4)          | None                | Sales Manager Name    |
| Sales Manager Name    | Sales_Manager_Name                    | String (30)         | Text                |                       |

48. After you entered all columns for the table, ensure you enable the Key Column option for the column Sales
Manager ID.
49. Click Save in the General menu.
50. You will be asked to confirm the Business Name as well as the Technical Name.
51. Click Save.
52. Click Deploy in the General Menu.
53. Use the Back option in top menu or as alternative you can click on your Space name to navigate back to the
home screen of the Data Builder.
  
## Summary

You've now created all tables that we need for our model and the overview in the Data Builder should look
like this:
<br>![](images/00_00_0038) UPLOAD 

Continue to - [Exercise 4 - Excercise 4 ](../ex4/README.md)
