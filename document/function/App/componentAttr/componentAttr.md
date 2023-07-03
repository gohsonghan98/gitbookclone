# componentAttr

## Description

Get the attribute of a component, such as its name, dimensions etc.

## Input / Parameter

| Name | Description | Input Type | Default | Options | Required |
| ------ | ------ | ------ | ------ | ------ | ------ |
| component | The name of the component to get attribute from | String | - | - | Partial (Yes if no 'componentId'.) |
| componentId | The id of the component to get attribute from | Stirng | - | - | Partial (Yes if no 'component'.) |
| attr | The attribute of the component | String | - | - | Yes |

__\* Note:__ Either component or componentId must have value in order for this function to work.

## Output

### Default Output

| Description | Output Type |
| ------ | ------ |
| The attribute to be obtained. | String |

### Parameter Output: {parameter-name}

The parameter output of the function.

## Video

Coming Soon.

## Example

The user wants to get the width attribute value of a button component.

### Steps

1. Draw a button component "btnComponentAttr"

    ![](../../../../document/function/App/componentAttr/componentAttr-step-1.png?raw=true)

2. In button click event, add a "console" then a "componentAttr" function.

    ![](../../../../document/function/App/componentAttr/componentAttr-step-2.png?raw=true)

![]({image-path}?raw=true)

### Result

The width value of button will be displayed, such as 164px.

## Links