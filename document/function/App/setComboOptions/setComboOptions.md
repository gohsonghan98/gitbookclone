# setComboOptions

## Description

Set the values or options for a combo box component.

## Input / Parameter

| Name | Description | Input Type | Default | Options | Required |
| ------ | ------ | ------ | ------ | ------ | ------ |
| combo | The name of the combo box component. | String | - | - | Partial (Yes if no 'comboId'.) |
| comboId | The id of the combo box component. | String | - | - | Partial (Yes if no 'combo'.) | 
| data | The list of options. | Array | - | - | Yes |
| valueField | The attribute name of the value inputs. | String | - | - | Yes |
| valueSeparator | The separator used to separate the value. | String | - | - | No |
| displayField | The attribute name of the dropdown values. | String | - | - | Yes |
| displaySeparator | The separator used to separate the display. | String | - | - | No |

__\* Note:__ Either combo or comboId must have value in order for this function to work.

## Output

### Default Output

| Description | Output Type |
| ------ | ------ |
| The dropdown values entered by the user. | String |

## Video

Coming Soon.

## Example

The user wants to choose the dropdown options from a combo box component.

### Steps (**not updated)

1. Draw a combo box "ComboBox617", a button "setComboOptions".

    ![](../../../../document/function/App/setComboOptions/setComboOptions-step-1.png?raw=true)
    

2. Call the function

    ![](../../../../document/function/App/setComboOptions/setComboOptions-step-2.png?raw=true)
    

3. Populate an array into data parameter by adding "toArray" & "toObject" functions.

    ![](../../../../document/function/App/setComboOptions/setComboOptions-step-3.png?raw=true)
    

4. Define the value field & display field.

    ![](../../../../document/function/App/setComboOptions/setComboOptions-step-4.png?raw=true)

### Result

The combo box "ComboBox617" have the display values of "abc" & "dfe" & the value of "abc is 1, value of "dfe" is 2.

![](../../../../document/function/App/setComboOptions/setComboOptions-result-1.png?raw=true)

## Links
