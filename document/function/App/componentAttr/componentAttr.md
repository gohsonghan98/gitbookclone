# componentAttr

### Description

Get the attribute of the component.

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

The user wants to get the width attribute value of a button component.

### Step

1. Draw a button component "btnComponentAttr"

    ![](../../../../document/function/App/componentAttr/componentAttr-step-1.png?raw=true)

2. In button click event, add a "console" then a "componentAttr" function.

    ![](../../../../document/function/App/componentAttr/componentAttr-step-2.png?raw=true)

### Result

The width value of button will be displayed eg 100%.

### Video

- N/A

### Notes

- You can use getComponent function to view all the available attribute of a component.