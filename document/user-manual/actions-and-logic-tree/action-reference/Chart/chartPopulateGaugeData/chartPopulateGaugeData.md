# chartPopulateGaugeData

### Description

Gauge chart, also known as dial chart or speedometer chart which uses a single needle to show information as a reading on a dial. This chart type is often used in executive dashboard reports to show key business indicators.

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required |
| ------ | ------ | ------ |------ | ------ |
| 1 | component | The name of the component that the details will be taken from. | String | Yes |
| 2 | componentId | The id of the component that the details will be taken from. | String | No |
| 3 | height | Height | Number | No |
| 4 | dataCaptions | dataCaptions | Array | No |
| 5 | data | Number | Array | Yes |

### Scenario / Use Case

The user wants to create a Gauge Chart.

### Step

1. Call the function "chartPopulateGaugeData" and define the value for      component, height, dataCaptions, and data. 
   <br>
   <ul>
   <li>component: chData</li>
   <li>height: 200</li>
   <li>dataCaptions: Speed</li>
  
   ![](../../../../document/function/Chart/chartPopulateGaugeData/chartPopulateGaugeData-step-1.png?raw=true)
   
   <li>data: 50</li>
   
   ![](../../../../document/function/Chart/chartPopulateGaugeData/chartPopulateGaugeData-step-2.png?raw=true)
 
### Result

 ![](../../../../document/function/Chart/chartPopulateGaugeData/chartPopulateGaugeData-result-1.png?raw=true)

### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A