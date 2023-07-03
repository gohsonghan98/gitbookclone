# getComponent

## Description

Retrive the details of the component.

## Input / Parameters

| Name | Description | Input Type | Default | Options | Required |
| ------ | ------ | ------ | ------ | ------ | ------ |
| component | The name of the component. | String | - | - | Partial (Yes if no 'componentId'.) |
| componentId | The id of the component. | String | - | - | Partial (Yes if no 'component'.) |

__\* Note:__ Either component or componentId must have value in order for this function to work.

## Output

### Default Output

| Description | Output Type |
| ------ | ------ |
| The details of the component selected. | String |

## Video

Coming Soon.

## Example

The user wants to view all the attributes or details of a component.

### Steps

1. Draw a button "ButtonGetCom".

    ![](../../../../document/function/App/getComponent/getComponent-step-1.png?raw=true)
    
2. Call the function.

    ![](../../../../document/function/App/getComponent/getComponent-step-2.png?raw=true)

### Result

In the console, the details of the component will appear as shown:

![](../../../../document/function/App/getComponent/getComponent-result-1.png?raw=true)

## Links
