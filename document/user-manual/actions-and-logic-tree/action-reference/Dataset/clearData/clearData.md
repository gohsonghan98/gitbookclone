# clearData 

### Description

Delete the local table.

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required |
| ------ | ------ | ------ |------ | ------ |
| 1 | dataset | The dataset name of the local table to be deleted.| String | Yes  |

### Scenario / Use Case

The user wants to delete the dataset "l_cart" from local table.

### Step

1. Create a local table "l_cart" and add value     for table.
   <br>
   Fields: item_code<br>
           item_name<br>
           price<br>
           quantity<br>
   
   ![](../../../../document/function/Dataset/clearData/clearData-step-1.png?raw=true)
  
   ![](../../../../document/function/Dataset/clearData/clearData-step-2.png?raw=true)
  
2. Call the function "clearData"and define the     dataset.
   <br>
   dataset: l_cart<br>
   
   ![](../../../../document/function/Dataset/clearData/clearData-step-3.png?raw=true)
   
### Result

![](../../../../document/function/Dataset/clearData/clearData-result-1.png?raw=true)

( Before call the function "clearData, the dataset "l_cart" still storing at local table. )

![](../../../../document/function/Dataset/clearData/clearData-result-2.png?raw=true)

( After call the function "clearData, the dataset "l_cart" was been clear from local table. )

### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A