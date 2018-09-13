# componentValue

### Description

Get the value of the component.

### Flowchart

![Flowchart](componentValue-flowchart-1.png?raw=true)

### Input / Parameters

| No | Name | Description | Data Type | Required |
| ------ | ------ | ------ |------ | ------ |
| 1 | component | The name of the component. | String | No __*__ | 
| 2 | componentId | The id of the component | String | No __*__ |
| 2 | value | The value | String | Yes |

__\* Note:__ Either No 1 or No 2 must have value in order for this function to work.

### Scenario / Use Case

The user wants to get the value from a text box component and display it in a label.

### Step

1. Drag and drop the following components: an edit text "txtName", a label "lblValue" and a button "btnGetValue" in a page.

    ![](componentValue-step-1.png?raw=true)

2. In the button 'click' event call the "setComponentValue" function and in the value parameter call "componentValue" function.

    ![](componentValue-step-2.png?raw=true)

### Result

The value in edit text will be display in the caption of the label.

![](componentValue-result-1.png?raw=true)

### Video

[![Video](componentValue-video-1.png?raw=true)](https://www.youtube.com/watch?v=yZepFLILR4E)

### Notes

- N/A