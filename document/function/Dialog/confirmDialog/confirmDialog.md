# confirmDialog

### Description

Displays a dialog box to get input/info from the user.

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required | 
| ------ | ------ | ------ |------ | ------ |
| 1 | title | Title of the confirmDialog. | String | Yes | 
| 2 | content | Info that you want the user be verify. | String | Yes |
| 3 | okCaption | The user clicked "OK | Boolean | Yes |
| 3 | cancelCaption | The user clicked "Cancel" | Boolean | Yes |

### Scenario / Use Case

The user wants to display a confirm box for get the verify or accept something.

### Step

1. Call the function "confirmDialog" and set the    value for information.
   <br>
   title: Confirm<br/>
   content: Are you sure you want to delete?<br/>
   okCaption: Delete<br/>
   cancelCaption: Exit<br/>
   
   ![](../../../../document/function/Dialog/confirmDialog/confirmDialog-step-1.png?raw=true)
   
   ![](../../../../document/function/Dialog/confirmDialog/confirmDialog-step-2.png?raw=true)
   
2. okCallback returns the input value if the       user clicks "OK" and set the variable and       the value.
   <br>
   var:Message<br/>
   value: Delete<br/>
   
   ![](../../../../document/function/Dialog/confirmDialog/confirmDialog-step-3.png?raw=true)

### Result

![](../../../../document/function/Dialog/confirmDialog/confirmDialog-result-1.png?raw=true)

### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A