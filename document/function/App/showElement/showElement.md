# showElement

## Description

Make a component visible on the screen.

## Input / Parameter

| Name | Description | Input Type | Default | Options | Required |
| ------ | ------ | ------ | ------ | ------ | ------ |
| component | The name of the component. | String | - | - | Partial (Yes if no 'componentId'.) |
| componentId | The id of the component. | String | - | - | Partial (Yes if no 'component'.) |

__\* Note:__ Either component or componentId must have value in order for this function to work.

## Output

### Default Output

| Description | Output Type |
| ------ | ------ |
| Checks whether the component is visible on screen. | Boolean |

## Video

Coming Soon.

## Example

The user wants to display a button component that was previously not visible on the screen.

### Steps

1. Call the function

    ![](../../../../document/function/App/showElement/showElement-step-1.png?raw=true)

### Result

The button will be shown in the mobile screen.

## Links