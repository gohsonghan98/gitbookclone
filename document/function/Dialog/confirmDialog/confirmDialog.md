# confirmDialog

### Description

Display a dialog box to ask for confirmation from the user.

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required | 
| ------ | ------ | ------ |------ | ------ |
| 1 | title | Title of the confirmDialog. | String | Yes | 
| 2 | content | Message in the dialog box. | String | Yes |
| 3 | okCaption | Caption for OK button. | String | No |
| 4 | cancelCaption | Caption for Cancel button. | String | No |
| 5 | okCallback | Functions to be executed when user clicks "OK" button. | [functionList] | No |
| 6 | cancelCallback | Functions to be executed when user clicks "Cancel" button. | [functionList] | No |

### Scenario / Use Case

The user wants to display a dialog box for ask the comfirmation from the user.

### Step

1. Call the function "confirmDialog" and set the    value for parameters.
   <br>
   title: Confirm<br/>
   content: Are you sure you want to delete?<br/>
   okCaption: Delete<br/>
   cancelCaption: Exit<br/>
   
   ![](../../../../document/function/Dialog/confirmDialog/confirmDialog-step-1.png?raw=true)
   
   ![](../../../../document/function/Dialog/confirmDialog/confirmDialog-step-2.png?raw=true)
   
2. Set a function in okCallback.
   <br>
   function:setVar<br/>
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