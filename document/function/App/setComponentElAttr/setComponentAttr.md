# setComponentElAttr

### Description

Set the element attribute of a component.

### Flowchart

- N/A

### Input / Parameters

| No | Name | Description | Data Type | Required |
| ------ | ------ | ------ |------ | ------ |
| 1 | component | The name of the component. | String | No __*__ | 
| 2 | componentId | The id of the component | String | No __*__ |
| 3 | attr | The attribute of component | String | Yes |
| 4 | value | The value of attribute | String | Yes |

__\* Note:__ Either No 1 or No 2 must have value in order for this function to work.

### Scenario / Use Case

The user override a specific element atrribute of a component.

### Step

1. Draw a button "btnSetComponentElAttr"

    ![](setComponentElAttr1.png?raw=true)
    
3. Call the function

    ![](setComponentElAttr2.png?raw=true)

### Result

The elemnet attribute "innerText" of a button "btnSetComponentElAttr" will have the value of "New Label".

![](setComponentElAttr3.png?raw=true)

### Video

- N/A
<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- User can use console -> getComponent to see all the element attribute of a component.