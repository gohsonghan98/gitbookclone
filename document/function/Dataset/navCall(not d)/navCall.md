# navCall 

### Description

Directly access or call a Microsoft Navision Web Service.

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required |
| ------ | ------ | ------ |------ | ------ |
| 1 | connector | Name of connector and created in the Services and Global Components page. | String | Yes  |
| 2 | type |  | String | Yes  |
| 3 | ent | The Web Service name to be called. | String | Yes |
| 4 | function | The function from the Web Service to be executed. | String | Yes |
| 5 | subfunction | This contains the additional parameters in the function being called. | Object | Yes |
| 6 | data | This contains the  parameter in the function being called. | Object | No |


### Scenario / Use Case

The user wants to call the navCall Web Service.

### Step

1. Call the function "rawCall" and define      the connector, path, method, set the        function "toObject"to options.
   <br>
   connector: rest<br>
   path: getCustomer<br>
   method: post<br>
   options: toObject<br>
   

2. Define toObject.
   <br>
   result: raw
  

   
3. Add a console after callback function for       display the response from console.   
    
   
 
### Result



### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A