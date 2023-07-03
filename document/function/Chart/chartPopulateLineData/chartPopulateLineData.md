# chartPopulateLineData

## Description

A line chart displays information as a series of data points called 'markers' connected by straight line segments. 

## Input / Parameter

| Name | Description | Input Type | Default | Options | Required |
| ------ | ------ | ------ | ------ | ------ | ------ |
| component | The name of the Chart component to take details from. | String | - | - | Yes |
| componentId | The id of the Chart component to take details from. | String | - | - | No | 
| dataCaptions | The legend for each data. | Array | - | - | No | 
| data | The data values for each legend. | Array | - | - | Yes |
| dataColors | The colors to be set for each legend. | Array | - | - | No |
| xCategories | The labels for the categories on the x-axis. | Array | - | - | No |
| yCaption | The label for the x-axis. | String | - | - | No |
| xCaption | The label for the y-axis. | String | - | - | No |
| showLabel | To show or hide label. | Boolean | - | - | No |
| zoom | To zoom or not to zoom. | Boolean | - | - | No |

## Output

### Default Output

| Description | Output Type |
| ------ | ------ |
| The line chart with details specified. | - |

## Video

Coming Soon.

## Example

The user wants to create a line chart.

### Steps

1. Call the function "chartPopulateLineData" and define the value for component, dataCaptions, data, dataColors, xCategories, yCaption, xCaption, showLabel and zoom.
   <br>
   <ul>
   <li>component: chData</li>
   
   ![](../../../../document/function/Chart/chartPopulateLineData/chartPopulateLineData-step-1.png?raw=true)
   
   <li>dataCaptions: toArray -></li> 
                            <ul>
                            <li>value1: Kevin </li>
                            <li>value2: Ann  </li>
                            <li>value3: Audrey  </li>
                            <li>value4: Nadine </li> 
                            </ul>
                            
   ![](../../../../document/function/Chart/chartPopulateLineData/chartPopulateLineData-step-2.png?raw=true)
   
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
                      
   ![](../../../../document/function/Chart/chartPopulateLineData/chartPopulateLineData-step-3.png?raw=true)
            
   <li>dataColors: toArray -></li> 
                           <ul>
                           <li>value1: BLACK </li>
                           <li>value2: PINK  </li>
                           <li>value3: BLUE  </li>
                           <li>value4: RED </li> 
                           </ul>
                            
   ![](../../../../document/function/Chart/chartPopulateLineData/chartPopulateLineData-step-4.png?raw=true)
    
    <li>xCategories: toArray-></li>
                            <ul>
                            <li>value1: Cat A </li>
                            <li>value2: Cat B </li>
                            <li>value3: Cat C </li>
                            <li>value4: Cat D </li> 
                            </ul>
                            
   ![](../../../../document/function/Chart/chartPopulateLineData/chartPopulateLineData-step-5.png?raw=true)
 
   <li>yCaption: Grade</li>
   <li>xCaption: Categories</li>
   <li>showLabel: true</li>
   <li>zoom: true</li>
   
   ![](../../../../document/function/Chart/chartPopulateLineData/chartPopulateLineData-step-6.png?raw=true)

### Result

The line chart with details specified by the user will be returned.

![](../../../../document/function/Chart/chartPopulateLineData/chartPopulateLineData-result-1.png?raw=true)

## Links

Coming Soon.