# inputDialog

### Description

Display a dialog box to get input/info from the user.

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required | 
| ------ | ------ | ------ |------ | ------ |
| 1 | title | Title of the inputDialog. | String | Yes | 
| 2 | type | Info that you want the user to input a value before entering a page. | String | Yes |
| 3 | value | Default value display at the input field. | Integer | No |
| 4 | okCallback | Function to be executed when user clicks "OK" button. | [functionList] | No |
| 5 | cancelCallback | Function to be executed when user clicks "Cancel" button. | [functionList] | No |

### Scenario / Use Case

The user wants to display an input dialog to let the user to key in the quantity.

### Step

1. Call the function "inputDialog" and set the           value.
   <br>
   title: Please Key In the Quantity<br/>
   type: quantity<br/>
  
   ![](../../../../document/function/Dialog/inputDialog/inputDialog-step-1.png?raw=true)
   
2. Set the function "setVar" in okCallback.
   <br>
   var: vCorrectValue <br>
   value: input
   
   ![](../../../../document/function/Dialog/inputDialog/inputDialog-step-2.png?raw=true)

### Result

![](../../../../document/function/Dialog/inputDialog/inputDialog-result-1.png?raw=true)

### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A