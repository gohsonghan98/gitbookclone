# componentElAttr

### Description

Get the element attribute of the component, such as name, value etc.

### Input / Parameter

| Name | Description | Input Type | Default | Options | Required |
| ------ | ------ | ------ | ------ | ------ | ------ |
| component | The name of the component to get attribute from | String | - | - | Partial (Yes if no 'componentId'.) |
| componentId | The id of the component to get attribute from | String | - | - | Partial (Yes if no 'component'.) |
| attr | The attribute of the component | String | - | - | Yes |

__\* Note:__ Either component or componentId must have value in order for this function to work.

## Output

### Default Output

| Description | Output Type |
| ------ | ------ |
| The element attribute to be obtained. | String |

### Parameter Output: {parameter-name}

The parameter output of the function.

## Video

Coming Soon.

## Example

The user wants to get the value from a text box component.

### Steps

1. Draw a edit text "txtA", a button "componentElAttr".

    ![](../../../../document/function/App/componentElAttr/componentElAttr-step-1.png?raw=true)

2. In button event, add a "console" then a "componentElAttr" function.

    ![](../../../../document/function/App/componentElAttr/componentElAttr-step-2.png?raw=true)

### Result

The value of the text box component will be displayed in the console.

## Links