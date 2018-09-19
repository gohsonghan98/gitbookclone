﻿# chartPopulateBarData

### Description

A diagram in which the numerical values of variables are represented by the height or length of lines or rectangles of equal width.

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required |
| ------ | ------ | ------ |------ | ------ |
| 1 | component | The name of the component that the details will be taken from. | String | Yes |
| 2 | componentId | The id of the component that the details will be taken from. | String | No |
| 3 | dataCaptions | dataCaptions | Array | Yes |
| 4 | data | Number | Array | Yes |
| 5 | dataColors | dataColors | Array | No |
| 6 | xCategories | X-Axis category | Array | Yes |
| 7 | yCaption | Y-Axis | String | Yes |
| 8 | xCaption | X-Axis | String | Yes |
| 9 | barRatio |  |  | Yes  |
| 10 | showLabel | True or false | Boolean | Yes |
| 11 | rotate | Rotation | - | Yes  |
| 12 | zoom | True or false | Boolean | Yes |

### Scenario / Use Case

The user wants to create a Bar Chart.

### Step

1. Call the function "chartPopulateBarData" and define the value            for component, dataCaptions, data, xCategories,                          yCaption, xCaption, barRatio, showLabel, rotate and zoom.
   <br>
   <ul>
   <li>component: chData</li>
  
   ![](../../../../document/function/Chart/chartPopulateBarDatanotd/chartPopulateBarData-step-1.png?raw=true)
   
   <li>dataCaptions: toArray -></li> 
                            <ul>
                            <li>value1: Kevin </li>
                            <li>value2: Ann  </li>
                            <li>value3: Audrey  </li>
                            <li>value4: Nadine </li> 
                            </ul>
   
   ![](../../../../document/function/Chart/chartPopulateBarDatanotd/chartPopulateBarData-step-2.png?raw=true)
   
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
  
   ![](../../../../document/function/Chart/chartPopulateBarDatanotd/chartPopulateBarData-step-3.png?raw=true)
   
   <li>xCategories: toArray-></li>
                            <ul>
                            <li>value1: Cat A </li>
                            <li>value2: Cat B </li>
                            </ul>
  
   ![](../../../../document/function/Chart/chartPopulateBarDatanotd/chartPopulateBarData-step-4.png?raw=true)
   
   <li>yCaption: Grade</li>
   <li>xCaption: Categories</li>
   <li>barRatio: 0.2</li>
   <li>showLabel: true</li>
   <li>rotate: true</li>
   <li>zoom: true</li>
   
   ![](../../../../document/function/Chart/chartPopulateBarDatanotd/chartPopulateBarData-step-5.png?raw=true)
  
   ![](../../../../document/function/Chart/chartPopulateBarDatanotd/chartPopulateBarData-step-6.png?raw=true)
    
### Result

 ![](../../../../document/function/Chart/chartPopulateBarDatanotd/chartPopulateBarData-result-1.png?raw=true)
 
### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A