# Exercise 14 - Best Salesperson

:memo: **Note:** This is a <strong>MANDATORY</strong>  Exercise

In this exercise, we will we will setup a story in SAP Analytics Cloud based on our Consumption Layer, and review who
our best salesperson is.

1. Log On to your SAP Analytics Cloud tenant.
2. Select the menu Stories in the left-hand panel
<br>![](images/00_00_0401.png) UPLOAD

3. Select the option Canvas to create a new Story.
4. You will be asked to select a Workspace.
5. Select the entry ANA161.
<br>![](images/00_00_0402.png) UPLOAD

6. In the toolbar click on “Data” (top left) to add data from SAP Data Warehouse Cloud to your Story
<br>![](images/00_00_0403.png) UPLOAD

7. Select the option Data From Data Source
<br>![](images/00_00_0404.png) UPLOAD

8. Open the list Connect to Live Data.
9. Select the entry SAP Data Warehouse Cloud
<br>![](images/00_00_0405.png) UPLOAD

10. You will be asked to select a Live Connection to SAP Data Warehouse Cloud.
<br>![](images/00_00_0406.png) UPLOAD

11. Please select the connection matching the SAP Data Warehouse Cloud system your selection. You can
choose from the following:<br><ul><li>DWCEU - for the SAP Data Warehouse System in Europe</li><li>DWCUS - for the SAP Data Warehouse System in US</li><li>DWCAPJ - for the SAP Data Warehouse System in APJ
<br>

12. When being asked to select a SPACE, select the Space your created previously – ANA161-XX.
<br>![](images/00_00_0407.png) UPLOAD
  
13. Click OK. 
<br>![](images/00_00_0408.png) UPLOAD

14. Afterwards you will be asked to select the Analytical Data Set or the Perspective from your Space.
15. For our third example, we will use the Perspective we created previously - Revenue by Store and Product
(Perspective)
16. Click OK.
17. Select the option to add a new Chart to the canvas.
18. Navigate to the Builder Panel on the right hand side.
<br>![](images/00_00_0409.png) UPLOAD

19. Click the option Add Dimension as part of the Dimensions section.
<br>![](images/00_00_0410.png) UPLOAD

20. Select the option Create Dimension Input Control.
<br>![](images/00_00_0411.png) UPLOAD
  
21. Select the entries:<br><ul><li>Dimension Store</li><li>Product</li><li>Sales Manager
<br>

22. Click OK.
23. On your canvas you will then be presented with a token for the newly created Dimension Input Control.
<br>![](images/00_00_0412.png) UPLOAD

24. Select the token and resize the token so that you can see all entries.
<br>![](images/00_00_0413.png) UPLOAD
  
25. Now use a double click on the header of the Dimension Input Control and enter: Please select a dimension.
26. Select the empty chart.
27. Navigate to the Business Builder Panel on the right hand side.
28. Click the Add Measure option for the Measures section.
29. Select measure Revenue.
30. Now open the More Actions menu for the chart.  
<br>![](images/00_00_0414.png) UPLOAD
  
31. Select the menu Rank.  
32. Select the option Top N Options.
<br>![](images/00_00_0415.png) UPLOAD
  
33. Set the Value to 10.
34. Click Apply. 
<br>![](images/00_00_0416.png) UPLOAD
  
35. You should now have a chart showing the Top 10 entries based on the dimension selected with the input
control and based on the Consumption Layer created in SAP Data Warehouse Cloud.
36. In the File menu select the option to save your story.
<br>![](images/00_00_0417.png) UPLOAD
  
37. Select the User folder that matches your assigned user number.
38. Enter a Name and Description.
39. Click OK.  


## Summary

Congratulations you have now completed the exercises for this session.


