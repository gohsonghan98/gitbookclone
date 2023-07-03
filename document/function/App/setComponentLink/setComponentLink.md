# setComponentLink

## Description

Add a hyperlink to a component which will open in a new tab in the web browser. 

## Input / Parameter

| Name | Description | Input Type | Default | Options | Required |
| ------ | ------ | ------ | ------ | ------ | ------ |
| component | The name of the component. | String | - | - | Partial (Yes if no 'componentId'.) |
| componentId | The id of the component. | String | - | - | Partial (Yes if no 'component'.) |
| link | The url of the website to open when the component is clicked. | String | - | - | Yes |

__\* Note:__ Either component or componentId must have value in order for this function to work.

## Output

### Default Output

| Description | Output Type |
| ------ | ------ |
| Checks if url is opened upon clicking on the component. | Boolean |

## Video

Coming Soon.

## Example

The user wants to open a hyperlink by clicking on the label component.

### Steps

1. Draw a label component & button component

    ![](../../../../document/function/App/setComponentLink/setComponentLink-step-1.png?raw=true)
    
2. Call the function.

    ![](../../../../document/function/App/setComponentLink/setComponentLink-step-2.png?raw=true)

### Result

The user will be redirected to https://emobiq.com after click on the label.

## Links