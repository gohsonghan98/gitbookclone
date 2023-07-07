# filterData

### Description

Get the data which filtered with a specific field name from a local table.

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required |
| ------ | ------ | ------ |------ | ------ |
| 1 | dataset | The dataset name of the local table.| String | Yes  |
| 2 | or | |  | No  |
| 3 | criteria1-5 | The Object. | Object | No__*__ |

__\* Note:__ At least one field from criteria1 to criteria5 must have value in order for this function to work.

### Scenario / Use Case

The user wants to display the data which name=Memory DDR RAM 8GB in dataset "l_item".

### Step

1. Call the function "filterData" and define the dataset. 
   <br>
   dataset: l_item<br>
  
    ![](../../../../document/function/Dataset/filterData/filterData-step-1.png?raw=true)
   
2. Set toObject function to criteria1 and define by, op and          value.<br>
   by: name<br>
   op: =<br>
   value: Memory DDR RAM 8GB
   
   ![](../../../../document/function/Dataset/filterData/filterData-step-2.png?raw=true)
    
### Result

 ![](../../../../document/function/Dataset/filterData/filterData-result-1.png?raw=true)

### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A