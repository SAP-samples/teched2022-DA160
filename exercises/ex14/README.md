# Exercise 14 - Best Salesperson

>:memo: **Note:** This is a <strong>MANDATORY</strong>  Exercise

---

In this exercise, we will we will setup a story in SAP Analytics Cloud based on our Consumption Layer, and review who
our best salesperson is.

1. Log On to your SAP Analytics Cloud tenant.
<br>![](images/00_00_0221.png) 
<br>

---

>:bulb: **Tip:** The system will ask you to resign in.

---

2. Select the menu Stories in the left-hand panel
3. Select the option Canvas to create a new Story.
<br>![](images/00_00_0201.png) 
4. Select "Classic Design Experience" when asked "What design mode would you like to use?"
<br>![](images/00_00_0222.png) 

5. In the toolbar click on “Data” (top left) to add data from SAP Data Warehouse Cloud to your Story
6. Select the option Data From Data Source.
<br>![](images/00_00_0204.png) 

7. Open the list Connect to Live Data.
8. Select the entry SAP Data Warehouse Cloud.
<br>![](images/00_00_0205.png) 

9. You will be asked to select Connection to SAP Data Warehouse Cloud.
10. Please select "SAPDWC" as the connection 
<br>![](images/00_00_0700.png)
<br>

11. When being asked to select your SPACE e.g. ***GE12345***.
12. Click OK. 

13. Afterwards you will be asked to select the Analytical Data Set or the Perspective from your Space.
14. For our third example, we will use the Perspective we created previously ***Revenue by Store and Product
(Perspective)***
15. Click OK.
<br>![](images/00_00_0418.png) 


16. Select the option to add a new Chart to the canvas.
<br>![](images/00_00_0207.png) 
  
19. Navigate to the Builder Panel on the right hand side.
<br>![](images/00_00_0410.png)   
  
20. Click the option Add Dimension as part of the Dimensions section.
<br>![](images/00_00_0209.png) 

21. Select the option Create Dimension Input Control.
<br>![](images/00_00_0303.png) 
  
22. Select the entries:<br><ul><li>Dimension Store</li><li>Product</li><li>Sales Manager
<br>
  
23. Click OK.
<br>![](images/00_00_0307.png) 
  
24. On your canvas you will then be presented with a token for the newly created Dimension Input Control.
<br>![](images/00_00_0412.png) 

25. Select the token and resize the token so that you can see all entries.
<br>![](images/00_00_0413.png) 
  
26. Now use a double click on the header of the Dimension Input Control and enter: Please select a dimension.
27. Select the empty chart.
28. Navigate to the Business Builder Panel on the right hand side.
29. Click the Add Measure option for the Measures section.
30. Select measure Revenue.
<br>![](images/00_00_0210.png)  
  
31. Now open the More Actions menu for the chart.  
32. Select the menu Rank.  
33. Select the option Top N Options.
<br>![](images/00_00_0415.png) 
  
34. Set the Value to 10.
35. Click Apply. 
<br>![](images/00_00_0416.png) 
  
36. You should now have a chart showing the Top 10 entries based on the dimension selected with the input
control and based on the Consumption Layer created in SAP Data Warehouse Cloud.
<br>![](images/00_00_0417.png) 
  
37. In the File menu select the option to save your story.
38. Select the User folder that matches your assigned user number.
39. Enter a Name and Description like ***Best Salesperson***.
40. Click OK.  


## Summary

:trophy: Congratulations you have now completed the exercises for this session! 


