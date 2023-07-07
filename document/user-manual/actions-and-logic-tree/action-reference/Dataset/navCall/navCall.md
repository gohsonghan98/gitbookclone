# navCall

### Description

Is a function that are needed when want to call Navfunction.

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required |
| ------ | ------ | ------ |------ | ------ |
| 1 | connector | Name of connector and created in the Services and Global Components page. | String | Yes  |
| 2 | type |  | String | No  |
| 3 | ent | | String | Yes  |
| 4 | function | The function from the Web Service to be executed. | String | No  |
| 5 | subfunction | TThe subfunction from the Web Service to be executed. | Object | No |
| 6 | data |  |  | No |

### Scenario / Use Case

The user wants to call the navCall Web Service.

### Step

1. Create NAV Connector in Services.<br>
   Name: nav<br>
   url: http://203.116.137.100:8047/DynamicsNAV90<br> 
   company: CRONUS Australia Pty. Ltd.
   user: chh\mobuser<br>
   password: ********<br>
   timeOut: 30000<br>
   
   ![](../../../../document/function/Dataset/navCall/navCall-step-1.png?raw=true)
   
   
2. Call the function "navCall".
   <br>
   
   ![](../../../../document/function/Dataset/navCall/navCall-step-2.png?raw=true)
   
  
3. Add a console after callback function for       display response from console.   
   
   ![](../../../../document/function/Dataset/navCall/navCall-step-3.png?raw=true)
 
### Result
   
   ![](../../../../document/function/Dataset/navCall/navCall-result-1.png?raw=true)

### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A