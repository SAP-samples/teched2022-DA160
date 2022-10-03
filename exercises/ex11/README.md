# Exercise 11 - Business Layer - Consumption Layer

In this exercise, we will create the consumption layer for our analytical story.

1. Select the menu option Business Builder on the left-hand side.
2. In case you are being asked, select the Space you created previously.
3. Select the category Consumption Models and Perspectives.
4. Select the option New Consumption Model.
5. Enter Revenue by Store and Product as Name.
<br>![](images/00_00_0111.png) UPLOAD

6. Click Step 2
<br>![](images/00_00_0112.png) UPLOAD

7. Select the entry Sales View – Analytical Dataset (Business Layer).
8. Click Create.
<br>![](images/00_00_0113.png) UPLOAD

9. Select the object for Dimension Store on the canvas.
<br>![](images/00_00_0114.png) UPLOAD

10. Use the “+” icon for the option Add Source Context.
11. For the Source Alias option, enter Dimension Store.
12. Click Create.
<br>![](images/00_00_0113.png) UPLOAD

13. On the right-hand side you should now see the dimension Store being listed under the category Dimension
Sources.
14. Now select the object for dimension Product on the canvas.
15. Use the “+” icon for the option Add Source Context.
16. For the Source Alias option, enter Product.
17. Click Create.
18. On the right-hand side you should now see dimension Product being listed under the category Dimension
Sources.
19. Now select the object for dimension Sales Manager on the canvas.
20. Use the “+” icon for the option Add Source Context.
21. For the Source Alias option, enter Sales Manager.
22. Click Create.
23. On the right-hand side you should now see the dimension Sales Manager being listed under the category
Dimension Sources.
24. Now select the object for dimension Time Dimension – Day (Business Layer) on the canvas.
25. Use the “+” icon for the option Add Source Context.
26. For the Source Alias option, enter Time Dimension – Day (Business Layer)
27. Click Create
28. On the right-hand side you should now see dimension Time Dimension – Day (Business Layer) being listed
under the category Dimension Sources.
29. Navigate to the tab General.
30. Enable the option Allow public data access.
31. Click Save (top right).
32. Navigate to the tab Measures.
33. Select the option Add Fact Source Measures.
<br>![](images/00_00_0114.png) UPLOAD

34. Select all measures.
<br>![](images/00_00_0115.png) UPLOAD

35. Click Apply.
36. Navigate to the tab Attributes.
37. Select the option Add Source Attributes.
<br>![](images/00_00_0116.png) UPLOAD

38. Select the following Attributes:<br><ul><li>Calendar Month</li><li>Calendar Quarter</li><li>Calendar Week</li><li>Country</li><li>Latitude</li><li>Longitude</li><li>Product Category Name</li><li>Product Name</li><li>Sales Manager Name</li><li>State Name</li><li>Store City</li><li>Store Location</li><li>Store Name</li><li>Transaction Date
<br>

<br>![](images/00_00_0117.png) UPLOAD

39. Click Apply.
40. Navigate to the tab Perspectives.
41. Click on the Data Preview option (top right corner).
<br>![](images/00_00_0118.png) UPLOAD

42. Open the context menu for the Perspective Fields header.
<br>![](images/00_00_0117.png) UPLOAD

43. Select the option Remove All Fields.
44. Drag and Drop the following Dimensions to the list of Perspective Fields:<br><ul><li>Product Name</li><li>Calendar Quarter</li><li>Product Category Name</li><li>Store City</li><li>Country</li><li>Sales Manager Name</li><li>Store Name</li><li>State Name
<br>

45. Open the list of entries for Composite Attributes on the left hand side.
46. Drag and drop dimension Transaction Date to the Perspective Fields.
47. Navigate to the list of Measures on the left hand side.
48. Select measure Cost and open the More menu (…).
<br>![](images/00_00_0118.png) UPLOAD

49. Select the option Add to Perspective.
50. Repeat the step for the measures Discount, Profit, and Revenue.
51. Click Save New (top right corner).
<br>![](images/00_00_0119.png) UPLOAD

52. Enter Revenue by Store and Product (Perspective) as Business Name.
53. Enter Revenue_by_Store_and_Product_Perspective as Technical Name
<br>![](images/00_00_0120.png) UPLOAD

54. Click Save.
We created the first perspective and just need to deploy the perspective now and can then leverage the
perspective in combination with SAP Analytics Cloud.
55. Click on the name of the Consumption Model in the top.
<br>![](images/00_00_0121.png) UPLOAD

56. Click on Data Preview (top right) to close the Data Preview.
<br>![](images/00_00_0122.png) UPLOAD

57. Navigate to the tab Perspectives.
<br>![](images/00_00_0123.png) UPLOAD

58. Use the icon on the far right for to deploy the Perspective.


## Summary

You've now created our first consumption layer and perspective, which can now be used in SAP Analytics Cloud.

Continue to - [Exercise 3 - Excercise 3 ](../ex3/README.md)
