# updateByMulti

### Description

Update multiple data with multiple field name.

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required |
| ------ | ------ | ------ |------ | ------ |
| 1 | dataset | Name of the dataset to be update in local table. | String | Yes  |
| 2 | filter | Filter details to be used in retrieving the data. | Object | Yes |
| 3 | orFilter | Filter details to be used in retrieving the data.  |  Object | No |
| 4 | data | The Object | Object | Yes |

### Scenario / Use Case

The user wants to update the name from ABC to A1A2A3A4 and tel from 1234567 to 1111111111 in dataset "l_customer".

### Step

1. Call the function "updateByMulti"and define the dataset.
   <br>
   dataset: l_customer<br>
   
2. Set toArray and toObject function to filter and define the             value of object.
   <br> filter:toArray-->toObject<br>
        id: 25<br>
        code: C12345<br>
         
    ![](../../../../document/function/Dataset/updateByMulti/updateByMulti-step-1.png?raw=true)
 
    ![](../../../../document/function/Dataset/updateByMulti/updateByMulti-step-2.png?raw=true)
    
3. Set toObject function to data and define the value of object.
   <br> name: A1A2A3A4<br>
        tel: 1111111111<br>
  
   ![](../../../../document/function/Dataset/updateByMulti/updateByMulti-step-3.png?raw=true)
   
### Result

   ![](../../../../document/function/Dataset/updateByMulti/updateByMulti-result-1.png?raw=true)
   ( Before update, the name is ABC and tel is 1234567 )
   
   ![](../../../../document/function/Dataset/updateByMulti/updateByMulti-result-2.png?raw=true)
   ( After update, the name changed to A1A2A3A4 and tel is 1111111111 )
   
### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A