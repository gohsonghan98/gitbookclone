# chartPopulatePieData

### Description

A pie chart is a divided circle, in which each slice of the pie represents a part of the whole.

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

### Scenario / Use Case

The user wants to create a Pie Chart.

### Step

1. Call the function "chartPopulatePieData" and define the value            for component, dataCaptions, and data.
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
                          <li>value2: 1 </li>
                          <li>value3: 2 </li>
                          <li>value4: 5 </li>
                          </ul>
                          <li>value2: ...... </li>
                          </ul>
  
   ![](../../../../document/function/Chart/chartPopulatePieData/chartPopulatePieData-step-3.png?raw=true)
    
### Result

 ![](../../../../document/function/Chart/chartPopulatePieData/chartPopulatePieData-result-1.png?raw=true)
 
### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A