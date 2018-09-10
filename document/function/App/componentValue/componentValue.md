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

1. Draw a edit text "txtA", a label "lblA", a button "componentValue".

    ![](componentValue-step-1.png?raw=true)

2. In button event, call the "setComponentValue" function and in value parameter call "componentValue" function.

    ![](componentValue-step-2.png?raw=true)

### Result

The value in edit text will be display in the caption of label.

![](componentValue-result-1.png?raw=true)

### Video

- N/A

### Notes

- N/A