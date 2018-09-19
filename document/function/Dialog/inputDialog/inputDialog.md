# inputDialog

### Description

Displays a dialog box to get input/info from the user.

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required | 
| ------ | ------ | ------ |------ | ------ |
| 1 | title | Title of the inputDialog. | String | Yes | 
| 2 | type | Info that you want the user to input a value before entering a page. | String | Yes |
| 3 | value | Value display at the input field | Integer | No |

### Scenario / Use Case

The user wants to display an input dialog for get the amount of the quantity.

### Step

1. Call the function "inputDialog" and set the           value for information.
   <br>
   title: Please Key In the Quantity<br/>
   type: quantity<br/>
  
   ![](../../../../document/function/Dialog/inputDialog/inputDialog-step-1.png?raw=true)
   
2. okCallback returns the input value if the             user clicks "OK" and set the variable.
   <br>
   var:vCorrectValue
   
   ![](../../../../document/function/Dialog/inputDialog/inputDialog-step-2.png?raw=true)

### Result

![](../../../../document/function/Dialog/inputDialog/inputDialog-result-1.png?raw=true)

### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A