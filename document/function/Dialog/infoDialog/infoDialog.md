# infoDialog

### Description

To display a dialog box and show information.

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required | 
| ------ | ------ | ------ |------ | ------ |
| 1 | title | Title of the infoDialog. | String | Yes | 
| 2 | content | Message in the dialog box. | String | Yes |
| 3 | disableTimer | true or false | Boolean | No  |
| 4 | timeOut | Interval of time  | Time | No  |
| 5 | okCaption | Caption for "OK" button.  | String | No  |
| 6 | okCallback | Function to be executed when user clicks on "OK" button.  | [functionList] | No  |

### Scenario / Use Case

The user wants to display an information dialog.

### Step

1. Call the function "infoDialog" and set the            value.
   <br>
   title: Message<br/>
   content: Updated Successful.<br/>
   timeOut: 30000<br/>
   
   ![](../../../../document/function/Dialog/infoDialog/infoDialog-step-1.png?raw=true)

### Result
The following info dialog will be displayed and shows the information. It will be time out in 30 seconds. <br>
   ![](../../../../document/function/Dialog/infoDialog/infoDialog-result-1.png?raw=true)
   
   
### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A