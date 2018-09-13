# setComponentAttr

### Description

Set the attribute of a component.

### Flowchart

- N/A

### Input / Parameters

| No | Name | Description | Data Type | Required |
| ------ | ------ | ------ |------ | ------ |
| 1 | component | The name of the component | String | No __*__ | 
| 2 | componentId | The id of the component | String | No __*__ |
| 3 | attr | The attribute of component | String | Yes |
| 4 | value | The value of attribute | String | Yes |

__\* Note:__ Either No 1 or No 2 must have value in order for this function to work.

### Scenario / Use Case

The user override a specific atrribute of a component.

### Step

1. Draw an edit text "txtTest", a button "setComponentAttr"

    ![](../../../../document/function/App/setComponentAttr/setComponentAttr-step-1.png?raw=true)
    
3. Call the function

    ![](../../../../document/function/App/setComponentAttr/setComponentAttr-step-2.png?raw=true)

### Result

The attribute "value" of the edit text "txtTest" will have the value of "abc".

![](../../../../document/function/App/setComponentAttr/setComponentAttr-result-1.png?raw=true)

### Video

- N/A
<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- User can use console -> getComponent to see all the attributes of a component.
