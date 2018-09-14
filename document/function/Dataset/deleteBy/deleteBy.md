# deleteBy

### Description

Removes a specific property from an object.

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required |
| ------ | ------ | ------ |------ | ------ |
| 1 | dataset | Name of the dataset in local table. | String | Yes  |
| 2 | by | Object name | String | Yes |
| 3 | value | The object value. | String | Yes |

### Scenario / Use Case

The user wants to delete the id=7 from dataset "l_customer".

### Step

1. Call the function "deleteBy"and define the dataset,  by, and      value.
   <br>
   dataset: l_customer<br>
   by: id<br>
   value: 7<br>
  
   ![](../../../../document/function/Dataset/deleteBy/deleteBy-step-1.png?raw=true)
   
### Result

![](../../../../document/function/Dataset/deleteBy/deleteBy-result-1.png?raw=true)
( Before delete, id=7 is still display in the dataset "l_customer" )

![](../../../../document/function/Dataset/deleteBy/deleteBy-result-2.png?raw=true)
( After delete, id=7 was being removed )
   
### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A