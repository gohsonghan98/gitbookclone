# chartPopulateDonutData

## Description

A donut chart displays quantitative data in a similar way to a pie chart, except it has an area of the centre cut out. This empty space can be used to display additional data or the title of the chart.

## Input / Parameter

| Name | Description | Input Type | Default | Options | Required |
| ------ | ------ | ------ | ------ | ------ | ------ |
| component | The name of the Chart component to take details from. | String | - | - | Yes |
| componentId | The id of the Chart component to take details from. | String | - | - | No | 
| title | Title of the chart. | String | - | - | No |
| dataCaptions | The legend for each data. | Array | - | - | No | 
| data | The data values for each legend. | Array | - | - | Yes |
| dataColors | The colors to be set for each legend. | Array | - | - | No |

## Output

### Default Output

| Description | Output Type |
| ------ | ------ |
| The donut chart with details specified. | - |

## Video

Coming Soon.

## Example

The user wants to create a donut chart.

### Steps

1. Call the function "chartPopulateDonutData" and define the value for component, title, dataCaptions, and data.
   <br>
   <ul>
   <li>component: chData</li>
   <li>title: Donut</li>
  
   ![](../../../../document/function/Chart/chartPopulateDonutData/chartPopulateDonutData-step-1.png?raw=true)
   
   <li>dataCaptions: toArray -></li> 
                            <ul>
                            <li>value1: Kevin </li>
                            <li>value2: Ann  </li>
                            <li>value3: Audrey  </li>
                            <li>value4: Nadine </li> 
                            </ul>
   
   ![](../../../../document/function/Chart/chartPopulateDonutData/chartPopulateDonutData-step-2.png?raw=true)
   
   </li><li>data: toArray -></li> 
                          <ul>
                          <li>value1: toArray </li>
                          <ul>
                          <li>value1: 1 </li>
                          </ul>
                          <li>value2: toArray </li>
                          <ul>
                          <li>value1: 2 </li>
                          </ul>
                          <li>value3: toArray </li>
                          <ul>
                          <li>value1: 3 </li>
                          </ul>
                          <li>value4: toArray </li>
                          <ul>
                          <li>value1: 4 </li>
                          </ul>
                          </ul>
                            
   ![](../../../../document/function/Chart/chartPopulateDonutData/chartPopulateDonutData-step-3.png?raw=true)

### Result

The donut chart with the details specified by the user will be returned.

 ![](../../../../document/function/Chart/chartPopulateDonutData/chartPopulateDonutData-result-1.png?raw=true)

## Links

Coming Soon.