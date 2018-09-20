# loadNext

### Description

Loads the following next records of the table or dataset.

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required |
| ------ | ------ | ------ |------ | ------ |
| 1 | dataset | The dataset name of the table to be loaded. | String | Yes  |
| 2 | datasetDisplay | |  | No |
| 3 | beforeCallback |  |  | No |

### Scenario / Use Case

The user wants to load the next of the data after a specific number of the data are loaded from dataset "l_customer".

### Step

1. Add a console for display the value"load    next called".

   ![](../../../../document/function/Dataset/loadNext/loadNext-step-1.png?raw=true)
 
2. Call the function "loadNext" and define     the dataset.
   <br>dataset: l_customer
    
   ![](../../../../document/function/Dataset/loadNext/loadNext-step-2.png?raw=true)

### Result

![](../../../../document/function/Dataset/loadNext/loadNext-result-1.png?raw=true) <br>

![](../../../../document/function/Dataset/loadNext/loadNext-result-2.png?raw=true) <br>

( When you call the function "loadNext", the rest of the data will be display it continuously. )

### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A