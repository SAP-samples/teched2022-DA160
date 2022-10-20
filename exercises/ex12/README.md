# Exercise 12 - Year over Year comparison

> :memo: **Note:** This is a <strong>MANDATORY</strong>  Exercise

---

In this exercise, we will setup a story in SAP Analytics Cloud, which allows us to do a Year over Year comparison
of our revenue information

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
14. For our first example, we will use the ***Analytical Data Set – Sales View – Analytical Dataset***.
15. Click OK.
<br>![](images/00_00_0208.png) 

16. Select the option to add a Chart.
<br>![](images/00_00_0207.png) 

17. Now select the newly created empty chart on the canvas.
18. Navigate to the Builder Panel on the right hand side.
<br>![](images/00_00_0203.png) 


19. Click Add Dimension as part of the Dimensions section.
<br>![](images/00_00_0209.png) 

20. Select Transaction Date.
<br>![](images/00_00_0202.png) 

21. Click Add Measure as part of the Measures section.
22. Select measure Revenue.
<br>![](images/00_00_0210.png) 

23. Now click on the hierarchy icon for dimension Transaction Date in the Builder Panel.
24. Select the option Set Hierarchy.
<br>![](images/00_00_0212.png) 

25. Select the entry Year, Quarter, Month, Day.
26. Click Set.
<br>![](images/00_00_0211.png) 

27. Now click on the hierarchy icon for dimension Transaction Date in the Builder Panel a second time.
28. Select the option Level 4 – which represents the Month level.
<br>![](images/00_00_0213.png)

29. Your chart should look similar to the image shown below.
<br>![](images/00_00_0214.png) 

30. So instead of looking at two years of data, we want to look at the current year – 2022 – and see the variance
compared to the last year data.
31. Click on the Filter icon for dimension Transaction Date.
32. Select the option Filter by Member.
<br>![](images/00_00_0215.png) 

33. Open the list of members and select the year 2022.
34. Click OK
<br>![](images/00_00_0216_2.png) 


35. Now click on the hierarchy icon for dimension Transaction Date in the Builder Panel.
36. Select the option Level 3 – which represents the Month level now as we selected a Year as entry point.
<br>![](images/00_00_0217.png) 

37. Open the More menu for the chart (top right corner).
38. Select the menu Compare to
39. Select the option Previous Year.
<br>![](images/00_00_0218.png) 

40. Your chart should look like this.
<br>![](images/00_00_0219.png) 

41. In the File menu select the option "save" to save your story.
42. Create a User folder that matches your Space name,  e.g. ***GE12345***.
43. Enter a Name and Description like ***Year over Year comparison***.
44. Click OK.

## Summary

You've now created your first SAP Anayltics Cloud Story on top of the data model you created earlier. 

Continue to - [Exercise 13: Revenue by Geography (requires Exercise 08 to be completed) ](../ex13/README.md)
