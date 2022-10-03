# Exercise 12 - Year over Year comparison

In this exercise, we will setup a story in SAP Analytics Cloud, which allows us to do a Year over Year comparison
of our revenue information

1. Log On to your SAP Analytics Cloud tenant.
2. Select the menu Stories in the left-hand panel
<br>![](/exercises/ex2/images/02_02_0201.png)

3. Select the option Canvas to create a new Story.
4. You will be asked to select a Workspace.
5. Select the entry ANA161.
<br>![](/exercises/ex2/images/02_02_0202.png)

6. In the toolbar click on “Data” (top left) to add data from SAP Data Warehouse Cloud to your Story
<br>![](/exercises/ex2/images/02_02_0203.png)

7. Select the option Data From Data Source.
<br>![](/exercises/ex2/images/02_02_0204.png)

8. Open the list Connect to Live Data.
9. Select the entry SAP Data Warehouse Cloud.
<br>![](/exercises/ex2/images/02_02_0205.png)

10. You will be asked to select a Live Connection to SAP Data Warehouse Cloud
<br>![](/exercises/ex2/images/02_02_0206.png)

11. Please select the connection matching the SAP Data Warehouse Cloud system your selection. You can
choose from the following:<br><ul><li>DWCEU - for the SAP Data Warehouse System in Europe</li><li>DWCUS - for the SAP Data Warehouse System in US</li><li>DWCAPJ - for the SAP Data Warehouse System in APJ
<br>

12. When being asked to select a SPACE, select the Space your created previously – ANA161-XX.
<br>![](/exercises/ex2/images/02_02_0207.png)

  























## Exercise 2.1 Sub Exercise 1 Description

After completing these steps you will have created...

1. Click here.
<br>![](/exercises/ex2/images/02_01_0010.png)

2.	Insert this line of code.
```abap
response->set_text( |Hello ABAP World! | ). 
```



## Exercise 2.2 Sub Exercise 2 Description

After completing these steps you will have...

1.	Enter this code.
```abap
DATA(lt_params) = request->get_form_fields(  ).
READ TABLE lt_params REFERENCE INTO DATA(lr_params) WITH KEY name = 'cmd'.
  IF sy-subrc = 0.
    response->set_status( i_code = 200
                     i_reason = 'Everything is fine').
    RETURN.
  ENDIF.

```

2.	Click here.
<br>![](/exercises/ex2/images/02_02_0010.png)

## Summary

You've now ...

Continue to - [Exercise 3 - Excercise 3 ](../ex3/README.md)
