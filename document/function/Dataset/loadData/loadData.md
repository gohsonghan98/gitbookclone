# loadData

### Description

Loads the data from local storage, staging database or 3rd party connector.

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required |
| ------ | ------ | ------ |------ | ------ |
| 1 | dataset | Name of the dataset to be read in local table. | String | Yes  |
| 2 | limit | The number of results to be returned or read. | Integer | No |
| 3 | page | Page | Number | No |
| 4 | filter | Filter details to be used in retrieving the data. | Object | Yes |
| 5 | orFilter | Filter details to be used in retrieving the data. | Object | No |
| 6 | order | Sort the data with the provided details. | Object | No |
| 7 | extra | |  | No |

### Scenario / Use Case

The user wants to load the data from dataset "l_customer".

### Step

1. Create a button, pannel, datalist and       label from component. 

   ![](../../../../document/function/Dataset/loadData/loadData-step-1.png?raw=true)

   ![](../../../../document/function/Dataset/loadData/loadData-step-2.png?raw=true)
<br>
   ( Set the dataset name "l_customer" for column Dataset. We assumed the dataset name have been created when you create local table in Services. )

   ![](../../../../document/function/Dataset/loadData/loadData-step-3.png?raw=true)

   ![](../../../../document/function/Dataset/loadData/loadData-step-4.png?raw=true)
<br>
   (  When you click the each label, set the field name to "code" "id" and "name" respectively for field column. )<br>
   
2. Call the function "dataFromString" and      define the dataset and string.<br>
   dataset: l_customer<br>
   string: [{"id":"1","code":"C20000","name":"Maxi-Teq","address":"300 Billings Drive","tel":"555-0110","term":"C.O.D"},{"id":"2","code":"C23900","name":"Parameter Technology","address":"908 Darby Road","tel":"555-0119","term":"C.O.D"}
   
   ![](../../../../document/function/Dataset/loadData/loadData-step-5.png?raw=true)

3. Call the function "loadData"and define      the dataset and limit.<br>
   dataset: l_customer<br>
   limit: 20

   ![](../../../../document/function/Dataset/loadData/loadData-step-6.png?raw=true)

### Result

![](../../../../document/function/Dataset/loadData/loadData-result-1.png?raw=true)

![](../../../../document/function/Dataset/loadData/loadData-result-2.png?raw=true)
( When you call the function "dataFromString", and put a string in json format.The outcome was shown in image above. )
 
![](../../../../document/function/Dataset/loadData/loadData-result-3.png?raw=true)
 <br>
( When you call the function "loadData", and set the limit is 20, therefore it will display the data from id 1-20 instead of until id 24. )

### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- For further information/steps, you can review   for the "loadNext" function.