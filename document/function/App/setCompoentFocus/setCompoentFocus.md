# setComponentFocus

## Description

Highlight a specific text on a component.

## Input / Parameter

| Name | Description | Input Type | Default | Options | Required |
| ------ | ------ | ------ | ------ | ------ | ------ |
| component | The name of the component. | String | - | - | Partial (Yes if no 'componentId'.) |
| componentId | The id of the component. | String | - | - | Partial (Yes if no 'component'.) |
| selectAllText | Highlight all the words in the component. | Boolean | - | - | No |
| hideKeyboard | Hide or display keyboard. | Boolean | - | - | No |

__\* Note:__ Either component or componentId must have value in order for this function to work.

### Default Output

| Description | Output Type |
| ------ | ------ |
| All the texts in the component are highlighted. | String |

## Video

Coming Soon.

## Example

The user wants to set focus on a component and highlight all the words in an edit text component.

### Steps

1. Draw an edit text "txtTest", a button "setComponenFocus".

    ![](../../../../document/function/App/setCompoentFocus/setCompoentFocus-step-1.png?raw=true)
    
2. Call the function.

    ![](../../../../document/function/App/setCompoentFocus/setCompoentFocus-step-2.png?raw=true)

### Result

The words "aaa" in the edit text will be selected.

![](../../../../document/function/App/setCompoentFocus/setCompoentFocus-result-1.png?raw=true)

## Links
