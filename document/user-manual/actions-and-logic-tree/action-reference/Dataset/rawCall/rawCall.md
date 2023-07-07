﻿# rawCall 

### Description

Directly access or call any REST API Web Service.

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required |
| ------ | ------ | ------ |------ | ------ |
| 1 | connector | Name of connector and created in the Services and Global Components page. | String | Yes  |
| 2 | path | The function from the Web Service to be executed. | String | Yes  |
| 3 | method | The REST method to be used. | String | Yes |
| 4 | options | Object | Object  | Yes |
| 5 | header | |  | No |
| 6 | data | This contains the  parameter in the function being called. | Object | No |
| 7 | file | This contains the file parameters in the function being called. | Object | No |
| 8 | extra |  |  | No |

### Scenario / Use Case

The user wants to call the RAW(REST) Web Service.

### Step

1. To create RAW(REST) Connector in Services and    define the Name and url.
   <br>Name: rest<br>
   url: http://203.116.137.100:51059/Training/Main.asmx ( Please refer to the picture below, there is a example of main web service.We have take one of the operation which is getCustomer as an example to apply for this function.)<br>
   
   ![](../../../../document/function/Dataset/rawCall/rawCall-step-1.png?raw=true)
   
   ![](../../../../document/function/Dataset/rawCall/rawCall-step-2.png?raw=true)

2. Call the function "rawCall" and define          the connector, path, method, set the            function "toObject"to options.
   <br>
   connector: rest<br>
   path: getCustomer<br>
   method: post<br>
   options: toObject<br>
   
   ![](../../../../document/function/Dataset/rawCall/rawCall-step-3.png?raw=true)

3. Define toObject.
   <br>
   result: raw
  
    ![](../../../../document/function/Dataset/rawCall/rawCall-step-4.png?raw=true)
   
4. Add a console after callback function for      display the response from console.   
    
    ![](../../../../document/function/Dataset/rawCall/rawCall-step-5.png?raw=true)
 
### Result

![](../../../../document/function/Dataset/rawCall/rawCall-result-1.png?raw=true)

### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A