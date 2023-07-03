# chartPopulatePieData

## Description

A pie chart is a circular statistical graph which is divided into slices, where each slice of the pie represents a part of the whole.

## Input / Parameter

| Name | Description | Input Type | Default | Options | Required |
| ------ | ------ | ------ | ------ | ------ | ------ |
| component | The name of the Chart component to take details from. | String | - | - | Yes |
| componentId | The id of the Chart component to take details from. | String | - | - | No | 
| dataCaptions | The legend for each data. | Array | - | - | No | 
| data | The data values for each legend. | Array | - | - | Yes |
| dataColors | The colors to be set for each legend. | Array | - | - | No |

## Output

### Default Output

| Description | Output Type |
| ------ | ------ |
| The pie chart with details specified. | - |

## Video

Coming Soon.

## Example

The user wants to create a pie chart.

### Steps

1. Call the function "chartPopulatePieData" and define the value for component, dataCaptions, and data.
   <br>
   <ul>
   <li>component: chData</li>
  
   ![](../../../../document/function/Chart/chartPopulatePieData/chartPopulatePieData-step-1.png?raw=true)
   
   <li>dataCaptions: toArray -></li> 
                            <ul>
                            <li>value1: Kevin </li>
                            <li>value2: Ann  </li>
                            <li>value3: Audrey  </li>
                            <li>value4: Nadine </li> 
                            </ul>
   
   ![](../../../../document/function/Chart/chartPopulatePieData/chartPopulatePieData-step-2.png?raw=true)
   
   </li><li>data: toArray -></li> 
                          <ul>
                          <li>value1: toArray </li>
                          <ul>
                          <li>value1: 5 </li>
                          </ul>
                          <li>value2: toArray </li>
                          <ul>
                          <li>value1: 9 </li>
                          </ul>
                          <li>value3: toArray </li>
                          <ul>
                          <li>value1: 8 </li>
                          </ul>
                          <li>value4: toArray </li>
                          <ul>
                          <li>value1: 3 </li>
                          </ul>
                          </ul>
  
   ![](../../../../document/function/Chart/chartPopulatePieData/chartPopulatePieData-step-3.png?raw=true)

### Result

The pie chart with the details specified by the user will be returned.

 ![](../../../../document/function/Chart/chartPopulatePieData/chartPopulatePieData-result-1.png?raw=true)

## Links

Coming Soon.