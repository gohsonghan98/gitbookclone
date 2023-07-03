# componentValue

## Description

Get the value of the component and be able to display in another component.

## Input / Parameter

| Name | Description | Input Type | Default | Options | Required |
| ------ | ------ | ------ | ------ | ------ | ------ |
| component | The name of the component that the value is retrieved from. | String | - | - | Partial (Yes if no 'componentId'.) |
| componentId | The id of the component that the value is retrieved from. | String | - | - | Partial (Yes if no 'component'.) |

__\* Note:__ Either component or componentId must have value in order for this function to work.

## Output

### Default Output

| Description | Output Type |
| ------ | ------ |
| The value of the component is returned. | String |

## Video

[![Video](../../../../document/function/App/componentValue/componentValue-video-1.png?raw=true)](https://www.youtube.com/watch?v=yZepFLILR4E)

## Example

The user wants to get the value from a text box component and display it in a label.

### Steps

1. Drag and drop the following components: an edit text "txtName", a label "lblValue" and a button "btnGetValue" in a page.

    ![](../../../../document/function/App/componentValue/componentValue-step-1.png?raw=true)

2. In the button 'click' event call the "setComponentValue" function and in the value parameter call "componentValue" function.

    ![](../../../../document/function/App/componentValue/componentValue-step-2.png?raw=true)

### Result

The value in edit text will be display in the caption of the label.

![](../../../../document/function/App/componentValue/componentValue-result-1.png?raw=true)

## Links