# setComponentAttr

## Description

Set a value to an attribute of a component.

## Input / Parameter

| Name | Description | Input Type | Default | Options | Required |
| ------ | ------ | ------ | ------ | ------ | ------ |
| component | The name of the component. | String | - | - | Partial (Yes if no 'componentId'.) |
| componentId | The id of the component. | String | - | - | Partial (Yes if no 'component'.) |
| attr | The attribute of the component. | String | - | - | Yes |
| value | The value of the attribute. | String | - | - | Yes |

__\* Note:__ Either component or componentId must have value in order for this function to work.

## Output

### Default Output

| Description | Output Type |
| ------ | ------ |
| The new value of the attribute of the component. | String |

## Video

Coming Soon.

## Example

The user wants to set a new value to an attribute of a component.

### Steps

1. Draw an edit text "txtTest", a button "setComponentAttr"

    ![](../../../../document/function/App/setComponentAttr/setComponentAttr-step-1.png?raw=true)
    
2. Call the function

    ![](../../../../document/function/App/setComponentAttr/setComponentAttr-step-2.png?raw=true)

### Result

The attribute "value" of the edit text "txtTest" will have the value of "abc".

![](../../../../document/function/App/setComponentAttr/setComponentAttr-result-1.png?raw=true)

## Links
