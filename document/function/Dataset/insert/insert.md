# Insert 

### Description

Insert a data in a local table.

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required |
| ------ | ------ | ------ |------ | ------ |
| 1 | dataset | Name of the dataset in local table to be insert. | String | Yes  |
| 2 | dt | Object name | Object | Yes |

### Scenario / Use Case

The user wants to insert the id=23 into the dataset "l_customer".

### Step

1. Call the function "insert"and define the dataset    and dt.
   <br>
   dataset: l_customer<br>
   
   ![](../../../../document/function/Dataset/insert/insert-step-1.png?raw=true)
  
2. Set toObject function to dt and define the value    of object.
   <br>
   dt: toObject<br>
   id: 23<br>
   code: C12345<br>
   name: ABC<br>
   
   ![](../../../../document/function/Dataset/insert/insert-step-2.png?raw=true)
   
### Result

![](../../../../document/function/Dataset/insert/insert-result-1.png?raw=true)
( Before insert, the id is until id=22 )

![](../../../../document/function/Dataset/insert/insert-result-2.png?raw=true)
( After insert, the id=23 successful add into the dataset "l_customer" )
   
### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A