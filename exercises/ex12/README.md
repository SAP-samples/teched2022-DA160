# Exercise 12 - Year over Year comparison

:memo: **Note:** This is a <strong>MANDATORY</strong>  Exercise

In this exercise, we will setup a story in SAP Analytics Cloud, which allows us to do a Year over Year comparison
of our revenue information

1. Log On to your SAP Analytics Cloud tenant.
2. Select the menu Stories in the left-hand panel
<br>![](images/00_00_0201.png) UPLOAD

3. Select the option Canvas to create a new Story.
4. You will be asked to select a Workspace.
5. Select the entry ANA161.
<br>![](images/00_00_0202.png) UPLOAD

6. In the toolbar click on “Data” (top left) to add data from SAP Data Warehouse Cloud to your Story
<br>![](images/00_00_0203.png) UPLOAD

7. Select the option Data From Data Source.
<br>![](images/00_00_0204.png) UPLOAD

8. Open the list Connect to Live Data.
9. Select the entry SAP Data Warehouse Cloud.
<br>![](images/00_00_0205.png) UPLOAD

10. You will be asked to select a Live Connection to SAP Data Warehouse Cloud
<br>![](images/00_00_0206.png) UPLOAD

11. Please select the connection matching the SAP Data Warehouse Cloud system your selection. You can
choose from the following:<br><ul><li>DWCEU - for the SAP Data Warehouse System in Europe</li><li>DWCUS - for the SAP Data Warehouse System in US</li><li>DWCAPJ - for the SAP Data Warehouse System in APJ
<br>

12. When being asked to select a SPACE, select the Space your created previously – ANA161-XX.
<br>![](images/00_00_0207.png) UPLOAD

13. Click OK. 
<br>![](images/00_00_0208.png) UPLOAD

14. Afterwards you will be asked to select the Analytical Data Set or the Perspective from your Space.
15. For our first example, we will use the Analytical Data Set – Sales View – Analytical Dataset.
16. Click OK.
17. Select the option to add a Chart.
18. Now select the newly created empty chart on the canvas.
19. Navigate to the Builder Panel on the right hand side.
<br>![](images/00_00_0209.png) UPLOAD

20. Click Add Dimension as part of the Dimensions section.
21. Select Transaction Date.
22. Click Add Measure as part of the Measures section.
23. Select measure Revenue.
<br>![](images/00_00_0210.png) UPLOAD

24. Now click on the hierarchy icon for dimension Transaction Date in the Builder Panel.
<br>![](images/00_00_0211.png) UPLOAD

25. Select the option Set Hierarchy.
<br>![](images/00_00_0212.png) UPLOAD

26. Select the entry Year, Quarter, Month, Day.
27. Click Set.
28. Now click on the hierarchy icon for dimension Transaction Date in the Builder Panel a second time.
<br>![](images/00_00_0213.png) UPLOAD

29. Select the option Level 4 – which represents the Month level.
30. Your chart should look similar to the image shown below.
<br>![](images/00_00_0214.png) UPLOAD

31. So instead of looking at two years of data, we want to look at the current year – 2021 – and see the variance
compared to the last year data.
32. Click on the Filter icon for dimension Transaction Date.
<br>![](images/00_00_0215.png) UPLOAD

33. Select the option Filter by Member.
34. Open the list of members and select the year 2021.
<br>![](images/00_00_0216.png) UPLOAD

35. Click OK
36. Now click on the hierarchy icon for dimension Transaction Date in the Builder Panel.
<br>![](images/00_00_0217.png) UPLOAD

37. Select the option Level 3 – which represents the Month level now as we selected a Year as entry point.
38. Open the More menu for the chart (top right corner).
<br>![](images/00_00_0218.png) UPLOAD

39. Select the menu Compare to
40. Select the option Previous Year.
41. Your chart should look like this.
<br>![](images/00_00_0219.png) UPLOAD

42. In the File menu select the option to save your story.
<br>![](images/00_00_0220.png) UPLOAD

43. Select the User folder that matches your assigned user number.
44. Enter a Name and Description.
45. Click OK.




## Summary

You've now ...FILL IN

Continue to - [Revenue by Geography (requires Exercise 08 to be completed) ](../ex13/README.md)
