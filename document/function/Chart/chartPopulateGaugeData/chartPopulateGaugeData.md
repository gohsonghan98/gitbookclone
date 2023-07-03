# chartPopulateGaugeData

## Description

A gauge chart, also known as dial chart or speedometer chart, uses a single needle to show information as a reading on a dial. This chart type is often used in executive dashboard reports to show key business indicators.

## Input / Parameter

| Name | Description | Input Type | Default | Options | Required |
| ------ | ------ | ------ | ------ | ------ | ------ |
| component | The name of the Chart component to take details from. | String | - | - | Yes |
| componentId | The id of the Chart component to take details from. | String | - | - | No | 
| height | The height of the chart. | Number | - | - | No |
| dataCaptions | The legend for each data. | Array | - | - | No | 
| data | The data values for each legend. | Array | - | - | Yes |

## Output

### Default Output

| Description | Output Type |
| ------ | ------ |
| The gauge chart with details specified. | - |

## Video

Coming Soon.

## Example

The user wants to create a gauge chart.

### Steps

1. Call the function "chartPopulateGaugeData" and define the value for component, height, dataCaptions, and data. 
   <br>
   <ul>
   <li>component: chData</li>
   <li>height: 200</li>
   <li>dataCaptions: Speed</li>
  
   ![](../../../../document/function/Chart/chartPopulateGaugeData/chartPopulateGaugeData-step-1.png?raw=true)
   
   <li>data: 50</li>
   
   ![](../../../../document/function/Chart/chartPopulateGaugeData/chartPopulateGaugeData-step-2.png?raw=true)

### Result

The gauge chart with the details specified by the user will be returned.

 ![](../../../../document/function/Chart/chartPopulateGaugeData/chartPopulateGaugeData-result-1.png?raw=true)

## Links

Coming Soon.