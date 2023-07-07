# componentElAttr

### Description

Get the element attribute of the component.

### Flowchart

- N/A

### Input / Parameters

| No | Name | Description | Data Type | Required |
| ------ | ------ | ------ |------ | ------ |
| 1 | component | The name of the component | String | No __*__ | 
| 2 | componentId | The id of the component | String | No __*__ |
| 2 | attr | The attribute of component | String | Yes |

__\* Note:__ Either No 1 or No 2 must have value in order for this function to work.

### Scenario / Use Case

The user wants to get the value from a text box component.

### Step

1. Draw a edit text "txtA", a button "componentElAttr".

    ![](../../../../document/function/App/componentElAttr/componentElAttr-step-1.png?raw=true)

2. In button event, add a "console" then a "componentElAttr" function.

    ![](../../../../document/function/App/componentElAttr/componentElAttr-step-2.png?raw=true)

### Result

The value in edit text will be displayed in console.

### Video

- N/A

### Notes

- N/A