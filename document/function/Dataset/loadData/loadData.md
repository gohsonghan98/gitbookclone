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
   string: [{"id":"1","code":"C20000","name":"Maxi-Teq","address":"300 Billings Drive","tel":"555-0110","term":"C.O.D"},{"id":"2","code":"C23900","name":"Parameter Technology","address":"908 Darby Road","tel":"555-0119","term":"C.O.D"},{"id":"3","code":"C25000","name":"Star Company","address":"Plynarenska","tel":"00421 2 582 56 33","term":"C.O.D"},{"id":"4","code":"C26000","name":"River Inc","address":"10 Eunos Road 8","tel":"0044 161 869 9000","term":"7 DAYS"},{"id":"5","code":"C30000","name":"Microchips","address":"45th Street","tel":"555-0103","term":"45 DAYS"},{"id":"6","code":"C40000","name":"Earthshaker Corporation","address":"208 Hollywood Ave","tel":"555-0122","term":"45 DAYS"},{"id":"7","code":"C42000","name":"Mashina Corporation","address":"400 Range Road","tel":"555-0126","term":"14 DAYS"},{"id":"8","code":"C50000","name":"ADA Technologies","address":"34 Highway 6","tel":"555-0129","term":"45 DAYS"},{"id":"9","code":"C60000","name":"SG Electronics","address":"67 Grant Ave","tel":"555-0130","term":"30 DAYS"},{"id":"10","code":"C70000","name":"Aquent Systems","address":"123 Kathryn Ave","tel":"555-0101","term":"30 DAYS"},{"id":"11","code":"C99998","name":"Web Customer","address":"NULL","tel":"NULL","term":"60 DAYS"},{"id":"12","code":"C99999","name":"One Time Customer","address":"NULL","tel":"NULL","term":"60 DAYS"},{"id":"13","code":"L10001","name":"Andreas Ackermann","address":"200 Morris Drive","tel":"555-0105","term":"60 DAYS"},{"id":"14","code":"L10002","name":"Werner Richter","address":"195 Blaine Blvd","tel":"555-0112","term":"30 DAYS"},{"id":"15","code":"V10000","name":"Acme Associates","address":"600 Eastern Blvd","tel":"555-0117","term":"90 DAYS"},{"id":"16","code":"V1010","name":"Far East Imports","address":"300 Elm Street","tel":"555-0123","term":"30 DAYS"},{"id":"17","code":"V20000","name":"Lasercom","address":"800 Billings Road","tel":"555-0132","term":"30 DAYS"},{"id":"18","code":"V21000","name":"Sea Corp","address":"Okruzna","tel":"00421 2 683 42 27","term":"30 DAYS"},{"id":"19","code":"V22000","name":"Ocean Computers","address":"Blk 35 Mandalay Road","tel":"0044 161 445 1895","term":"C.O.D"},{"id":"20","code":"V23000","name":"Anthony Smith","address":"10 Blaine Drive","tel":"555-0107","term":"C.O.D"},{"id":"21","code":"V30000","name":"Blockies Corporation","address":"721 45th Street","tel":"555-0109","term":"C.O.D"},{"id":"22","code":"V50000","name":"Lumarx","address":"78 S. Willow St","tel":"555-0125","term":"7 DAYS"},{"id":"23","code":"V60000","name":"CTI Computers","address":"536 Union Blvd","tel":"555-0115","term":"45 DAYS"},{"id":"24","code":"V70000","name":"SMD Technologies","address":"9 Weare Turnpike","tel":"555-0135","term":"45 DAYS"}]
   
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