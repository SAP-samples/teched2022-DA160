# Exercise 13 - Geographic Revenue Distribution

In this exercise, we will we will setup a story in SAP Analytics Cloud, which allows us to view the measures along a
geographic map.

1. Log On to your SAP Analytics Cloud tenant.
2. Select the menu Stories in the left-hand panel
<br>![](images/00_00_0301.png) UPLOAD

3. Select the option Canvas to create a new Story.
4. You will be asked to select a Workspace.
5. Select the entry ANA161.
<br>![](images/00_00_0302.png) UPLOAD

6. In the toolbar click on “Data” (top left) to add data from SAP Data Warehouse Cloud to your Story.
<br>![](images/00_00_0303.png) UPLOAD

7. Select the option Data From Data Source.
<br>![](images/00_00_0304.png) UPLOAD

8. Open the list Connect to Live Data.
9. Select the entry SAP Data Warehouse Cloud.
<br>![](images/00_00_0305.png) UPLOAD

10. You will be asked to select a Live Connection to SAP Data Warehouse Cloud.
<br>![](images/00_00_0306.png) UPLOAD

11. Please select the connection matching the SAP Data Warehouse Cloud system your selection. You can
choose from the following:<br><ul><li>DWCEU - for the SAP Data Warehouse System in Europe</li><li>DWCUS - for the SAP Data Warehouse System in US</li><li>DWCAPJ - for the SAP Data Warehouse System in APJ
<br>

12. When being asked to select a SPACE, select the Space your created previously – ANA161-XX.
<br>![](images/00_00_0306.png) UPLOAD

13. Click OK.
<br>![](images/00_00_0307.png) UPLOAD

14. Afterwards you will be asked to select the Analytical Data Set or the Perspective from your Space.
15. For our second example, we will use the Analytical Data Set – Sales View – Analytical Dataset.
16. Click OK.
17. Select the option to add a Geo Map.
18. Resize the map, so that it uses the complete screen.
19. In the panel on the right hand side, select the option “Add Layer” for the Content Layer option.
<br>![](images/00_00_0308.png) UPLOAD

20. As we only have one dataset right now, the data set from SAP Data Warehouse Cloud will be assigned to
the new map layer.
<br>![](images/00_00_0309.png) UPLOAD

21. Click on Add Location Dimension for the Location Dimension area
<br>![](images/00_00_0310.png) UPLOAD

22. Select the option Store Location. This is the store location dimension we created previously based on the
longitude and latitude values for the store dimension.
23. Click on Add Measure for the Bubble Size.
24. Select measure Revenue.
25. Click Add Measure / Dimension for the Bubble Color
26. Select measure Profit.
27. Now open the details for the measure Profit as part of the Bubble Color
<br>![](images/00_00_0311.png) UPLOAD

28. Open the list of Color Palette.
<br>![](images/00_00_0312.png) UPLOAD

29. Select the second entry from the Diverging category going from Red to Green.
30. Now open the details for the Bubble Size definition.
<br>![](images/00_00_0313.png) UPLOAD

31. Set the size to 35%.
32. Your map should look like this.
<br>![](images/00_00_0314.png) UPLOAD

33. In the File menu select the option to save your story.
<br>![](images/00_00_0315.png) UPLOAD

34. Select the User folder that matches your assigned user number.
35. Enter a Name and Description.
36. Click OK.


## Summary

You've now ...FILL IN

Continue to - [Best Salesperson (requires Exercise 11 to be completed) ](../ex14/README.md)
