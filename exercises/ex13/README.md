# Exercise 13 - Geographic Revenue Distribution

>:memo: **Note:** This is a <strong>MANDATORY</strong>  Exercise

---

In this exercise, we will we will setup a story in SAP Analytics Cloud, which allows us to view the measures along a
geographic map.

1. Log On to your SAP Analytics Cloud tenant.
<br>![](images/00_00_0221.png) 
<br>

---

:bulb: **Tip:** The system will ask you to resign in.

---

2. Select the menu Stories in the left-hand panel
3. Select the option Canvas to create a new Story.
<br>![](images/00_00_0201.png) 
4. Select "Classic Design Experience" when asked "What design mode would you like to use?"
<br>![](images/00_00_0222.png) 

5. In the toolbar click on “Data” (top left) to add data from SAP Data Warehouse Cloud to your Story.
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
15. Afterwards you will be asked to select the Analytical Data Set or the Perspective from your Space.
16. For our second example, we will use the Analytical Data Set – Sales View – Analytical Dataset.
17. Click OK.
<br>![](images/00_00_0208.png)   
  
18. Select the option to add a Geo Map.
<br>![](images/00_00_0306.png) 
  
19. Resize the map, so that it uses the complete screen.
20. In the panel on the right hand side, select the option “Add Layer” for the Content Layer option.
<br>![](images/00_00_0302.png) 

21. As we only have one dataset right now, the data set from SAP Data Warehouse Cloud will be assigned to
the new map layer.
22. Click on Add Location Dimension for the Location Dimension area
23. Select the option Store Location. This is the store location dimension we created previously based on the
longitude and latitude values for the store dimension.
<br>![](images/00_00_0310.png) 

24. Click on Add Measure for the Bubble Size.
25. Select measure Revenue.
<br>![](images/00_00_0309.png) 


26. Click Add Measure / Dimension for the Bubble Color
27. Select measure Profit.
<br>![](images/00_00_0316.png) 

28. Now open the details for the measure Profit as part of the Bubble Color
29. Open the list of Color Palette.
30. Select the second entry from the Diverging category going from Red to Green.
<br>![](images/00_00_0312.png) 

31. Now open the details for the Bubble Size definition.
32. Set the size to 35%.
<br>![](images/00_00_0311.png) 

33. Your map should look like this.
<br>![](images/00_00_0314.png) 

34. In the File menu select the option to save your story.
35. Select the User folder that matches your assigned user number.
36. Enter a Name and Description like ***Geographic Revenue Distribution***.
37. Click OK.


## Summary

You've now created your second story based on the live connection to your data models in SAP Data Warehouse Cloud. 

Continue to - [Best Salesperson (requires Exercise 11 to be completed) ](../ex14/README.md)
