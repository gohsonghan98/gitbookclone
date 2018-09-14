# dataFromString


### Description

This will replace all of the existing records in the local table with the new ones, the values inserted must be in a json format.

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required 
| ------ | ------ | ------ |------ | ------ |
| 1 | dataset | Name of the dataset to be read in local table.| String | Yes  |
| 2 | string | The values to be inserted in the local table. | String  | Yes |
| 3 | append | Inserts specified content at the end of the selected elements. | String  | No |

### Scenario / Use Case

The user wants to replace all the existing records in the local table with the new ones.</br>

### Step

1. Call the function "dataFromString", set            the dataset    and set    the function             "jsonDecode" to string.<br>
   dataset: l_customer<br />
   string: jsonDecode<br/>
    
    ![](../../../../document/function/Dataset/dataFromString/dataFromString-step-1.png?raw=true)
    
2. Call the function "toArray" and set the            function "toObject" to string and define    the    id and code.<br>
   string: toObject<br />
   id: 1<br>
   code: C00013<br/>
   id: 2<br>
   code: C00014<br>
   id: 3<br>
   code: C00015<br>
   id: 4<br>
   code: C00016<br>
   
   ![](../../../../document/function/Dataset/dataFromString/dataFromString-step-2.png?raw=true)
   
   ![](../../../../document/function/Dataset/dataFromString/dataFromString-step-3.png?raw=true)
   
   ![](../../../../document/function/Dataset/dataFromString/dataFromString-step-4.png?raw=true)
   
   ![](../../../../document/function/Dataset/dataFromString/dataFromString-step-5.png?raw=true)
   
   ![](../../../../document/function/Dataset/dataFromString/dataFromString-step-6.png?raw=true)
  
    
### Result

![](../../../../document/function/Dataset/dataFromString/dataFromString-result-1.png?raw=true)<br>

![](../../../../document/function/Dataset/dataFromString/dataFromString-result-2.png?raw=true)

### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A