# modalDialog.md

### Description

To display an information on dialog box.

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required | 
| ------ | ------ | ------ |------ | ------ |
| 1 | snippet | Title of the snippet. | String | Yes | 
| 2 | show | to show the snippet. | String | Yes |


### Scenario / Use Case

User want to display an information on dialog box.

### Step

1. Call the function.
   <br>
  
   ![](../../../../document/function/Dialog/modalDialog/modalDialog-step-1.png?raw=true)
   
2. okCallback returns the input value if the             user clicks "OK" and set the variable.
   <br>
   var:vCorrectValue
   value:input
   
   ![](../../../../document/function/Dialog/inputDialog/inputDialog-step-2.png?raw=true)

### Result

![](../../../../document/function/Dialog/inputDialog/inputDialog-result-1.png?raw=true)

### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A