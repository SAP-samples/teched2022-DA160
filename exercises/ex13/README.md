# Exercise 13 - Geographic Revenue Distribution

:memo: **Note:** This is a <strong>MANDATORY</strong>  Exercise

In this exercise, we will we will setup a story in SAP Analytics Cloud, which allows us to view the measures along a
geographic map.

1. Log On to your SAP Analytics Cloud tenant.
<br>![](images/00_00_0221.png) 
<br>
:bulb: **Tip:** The system will ask you to resign in.


2. Select the menu Stories in the left-hand panel
3. Select "Classic Design Experience" when asked "What design mode would you like to use?"
<br>![](images/00_00_0222.png) 
<br>

4. Select the option Canvas to create a new Story.
<br>![](images/00_00_0201.png) 

5. You will be asked to select a Workspace.
6. Select the entry ANA161.????
7. In the toolbar click on “Data” (top left) to add data from SAP Data Warehouse Cloud to your Story.
8.Select the option Data From Data Source.
<br>![](images/00_00_0204.png) 

9. Open the list Connect to Live Data.
10. Select the entry SAP Data Warehouse Cloud.
<br>![](images/00_00_0205.png) 

11. You will be asked to select a Live Connection to SAP Data Warehouse Cloud.
12. Please select the connection matching the SAP Data Warehouse Cloud system your selection. You can
choose from the following:<br><ul><li>DWCEU - for the SAP Data Warehouse System in Europe</li><li>DWCUS - for the SAP Data Warehouse System in US</li><li>DWCAPJ - for the SAP Data Warehouse System in APJ????
<br>

13. When being asked to select a SPACE, select the Space your created previously – ANA161-XX.????
14. Click OK.
15. Afterwards you will be asked to select the Analytical Data Set or the Perspective from your Space.
16. For our second example, we will use the Analytical Data Set – Sales View – Analytical Dataset.
17. Click OK.
<br>![](images/00_00_0208.png)   
  
18. Select the option to add a Geo Map.
19. Resize the map, so that it uses the complete screen.
20. In the panel on the right hand side, select the option “Add Layer” for the Content Layer option.
<br>![](images/00_00_0308.png) UPLOAD

21. As we only have one dataset right now, the data set from SAP Data Warehouse Cloud will be assigned to
the new map layer.
<br>![](images/00_00_0309.png) UPLOAD

22. Click on Add Location Dimension for the Location Dimension area
<br>![](images/00_00_0310.png) UPLOAD

23. Select the option Store Location. This is the store location dimension we created previously based on the
longitude and latitude values for the store dimension.
24. Click on Add Measure for the Bubble Size.
25. Select measure Revenue.
26. Click Add Measure / Dimension for the Bubble Color
27. Select measure Profit.
28. Now open the details for the measure Profit as part of the Bubble Color
<br>![](images/00_00_0311.png) UPLOAD

29. Open the list of Color Palette.
<br>![](images/00_00_0312.png) UPLOAD

30. Select the second entry from the Diverging category going from Red to Green.
31. Now open the details for the Bubble Size definition.
<br>![](images/00_00_0313.png) UPLOAD

32. Set the size to 35%.
33. Your map should look like this.
<br>![](images/00_00_0314.png) UPLOAD

34. In the File menu select the option to save your story.
<br>![](images/00_00_0315.png) UPLOAD

35. Select the User folder that matches your assigned user number.
36. Enter a Name and Description.
37. Click OK.


## Summary

You've now ...FILL IN

Continue to - [Best Salesperson (requires Exercise 11 to be completed) ](../ex14/README.md)
