# updateBy

### Description

Update a data with a specific field name.

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required |
| ------ | ------ | ------ |------ | ------ |
| 1 | dataset | Name of the dataset to be update in local table. | String | Yes  |
| 2 | by | Object name | String | Yes |
| 3 | operator | To assign values to a variable. |  | Yes |
| 4 | value | The object value. | String | Yes |
| 5 | data | The Object | Object | Yes |

### Scenario / Use Case

The user wants to update the code from E1234567 to E1234 in dataset "l_item".

### Step

1. Call the function "updateBy"and define the         dataset, by,operator and value.
   <br>
   dataset: l_item<br>
   by: code<br>
   operator: =<br>
   value: E1234567<br>
   
   ![](../../../../document/function/Dataset/updateBy/updateBy-step-1.png?raw=true)
 
 2. Set toObject function to data and define the      value of object.
    <br> data: toObject<br>
         code: E1234<br>
 
    ![](../../../../document/function/Dataset/updateBy/updateBy-step-2.png?raw=true)
   
### Result

   ![](../../../../document/function/Dataset/updateBy/updateBy-result-1.png?raw=true)
   ( Before update, the code is E1234567 )
   
   ![](../../../../document/function/Dataset/updateBy/updateBy-result-2.png?raw=true)
   ( After update, the code changed to E1234 )
   
### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A