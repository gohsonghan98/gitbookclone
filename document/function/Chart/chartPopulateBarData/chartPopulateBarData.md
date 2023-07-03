# chartPopulateBarData

## Description

A bar chart displays categorical data with rectangular bars. The bars can be plotted vertically or horizontally by defining the "rotate" parameter. It is used to compare values across different sub-groups and each sub-group is usually coloured or shaded differently to distinguish between them.

## Input / Parameter

| Name | Description | Input Type | Default | Options | Required |
| ------ | ------ | ------ | ------ | ------ | ------ |
| component | The name of the Chart component to take details from. | String | - | - | Yes |
| componentId | The id of the Chart component to take details from. | String | - | - | No | 
| dataCaptions | The legend for each data. | Array | - | - | No | 
| data | The data values for each legend. | Array | - | - | Yes |
| dataColors | The colors to be set for each legend. | Array | - | - | No |
| xCategories | Labels for the categories on the x-axis. | Array | - | - | No |
| yCaption | The label for the x-axis. | String | - | - | No |
| xCaption | The label for the y-axis. | String | - | - | No |
| barRatio | Bin width?? | Number | - | - | No |
| showLabel | To show or hide label. | Boolean | - | - | No |
| rotate | To display chart horizontally or vertically. | Boolean | - | - | No |
| zoom | To zoom or not to zoom. | Boolean | - | - | No |

## Output

### Default Output

| Description | Output Type |
| ------ | ------ |
| The bar chart with details specified. | - |

## Video

Coming Soon.

## Example

The user wants to create a bar chart.

### Steps

1. Call the function "chartPopulateBarData" and define the value for component, dataCaptions, data, xCategories, yCaption, xCaption, barRatio, showLabel, rotate and zoom.
   <br>
   <ul>
   <li>component: chData</li>
  
   ![](../../../../document/function/Chart/chartPopulateBarData/chartPopulateBarData-step-1.png?raw=true)
   
   <li>dataCaptions: toArray -></li> 
                            <ul>
                            <li>value1: Kevin </li>
                            <li>value2: Ann  </li>
                            <li>value3: Audrey  </li>
                            <li>value4: Nadine </li> 
                            </ul>
   
   ![](../../../../document/function/Chart/chartPopulateBarData/chartPopulateBarData-step-2.png?raw=true)
   
   </li><li>data: toArray -></li> 
                          <ul>
                          <li>value1: toArray </li>
                          <ul>
                          <li>value1: 5 </li>
                          <li>value2: 1 </li>
                          <li>value3: 2 </li>
                          <li>value4: 5 </li>
                          </ul>
                          <li>value2: ...... </li>
                          </ul>
  
   ![](../../../../document/function/Chart/chartPopulateBarData/chartPopulateBarData-step-3.png?raw=true)
   
   <li>xCategories: toArray-></li>
                            <ul>
                            <li>value1: Cat A </li>
                            <li>value2: Cat B </li>
                            <li>value3: ... </li>
                            </ul>
  
   ![](../../../../document/function/Chart/chartPopulateBarData/chartPopulateBarData-step-4.png?raw=true)
   
   <li>yCaption: Grade</li>
   <li>xCaption: Categories</li>
   <li>barRatio: 0.2</li>
   <li>showLabel: true</li>
   <li>rotate: true</li>
   <li>zoom: true</li>
   
   ![](../../../../document/function/Chart/chartPopulateBarData/chartPopulateBarData-step-5.png?raw=true)
  
   ![](../../../../document/function/Chart/chartPopulateBarData/chartPopulateBarData-step-6.png?raw=true)

### Result

The bar chart with the details specified by the user will be returned.

 ![](../../../../document/function/Chart/chartPopulateBarData/chartPopulateBarData-result-1.png?raw=true)

## Links

Coming Soon.