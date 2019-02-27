# deleteByMulti

### Description

Removes multiple property from an object.

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required |
| ------ | ------ | ------ |------ | ------ |
| 1 | dataset | Name of the dataset to be update in local table. | String | Yes  |
| 2 | filter | Filter details to be used in retrieving the data. | Object | Yes |
| 3 | orFilter | Filter details to be used in retrieving the data.  |  Object | No |

### Scenario / Use Case

The user wants to delete the field id=25 and name=ABC from dataset "l_customer".

### Step

1. Call the function "deleteByMulti"and define the dataset.
   <br>
   dataset: l_customer<br>
   
2. Set toArray and toObject function to filter and define the         value of object.
   <br> filter:toArray-->toObject<br>
        id: 25<br>
        name: A1A2A3A4<br>
         
    ![](../../../../document/function/Dataset/deleteByMulti/deleteByMulti-step-1.png?raw=true)
 
    ![](../../../../document/function/Dataset/deleteByMulti/deleteByMulti-step-2.png?raw=true)
    
### Result


  ![](../../../../document/function/Dataset/deleteByMulti/deleteByMulti-result-1.png?raw=true)
  ( Before delete, the id=25; name= A1A2A3A4 is still store in the local table. )
   
  ![](../../../../document/function/Dataset/deleteByMulti/deleteByMulti-result-2.png?raw=true)
  ( After delete, id=25; name= A1A2A3A4 was removed in local table.)
   
### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A