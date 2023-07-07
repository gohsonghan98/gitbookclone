# acumaticaCall 

### Description

AcumaticaCall is the function to generate the token session.

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required |
| ------ | ------ | ------ |------ | ------ |
| 1 | connector | Name of connector and created in the Services and Global Components page. | String | Yes  |
| 2 | ent | The Web Service name to be called. | String | No  |
| 3 | function | The function name to be called. | String | Yes  |
| 4 | data |   | Object | No |
| 5 | files |   | String | No  |
| 6 | extra |   | String | No  |

### Scenario / Use Case

User want to generate token session for ASP.Net

### Step

1. Create Acumatica Connector in Services and define the name, url, basepath, company, user, password and timeOut.
   <br>Name: connAcumatica<br>
   url: http://203.116.137.100:8011<br>( Please refer to the picture below, there is a example of main web service.We have take one of the operation as an example to apply for this function.)<br>
   basepath: /AcumaticaERP/entity/Orangekloud/18.200.001<br>
   company: mydemo<br>
   user: admin<br>
   password: ***<br>
   timeOut: 30000
   
   ![](../../../../document/function/Dataset/acumaticaCall/acumaticaCall-step-1.png?raw=true)
   
2. Call the function "acumaticaCall".
   <br>
   
   ![](../../../../document/function/Dataset/acumaticaCall/acumaticaCall-step-2.png?raw=true)
   
   ![](../../../../document/function/Dataset/acumaticaCall/acumaticaCall-step-3.png?raw=true)
   
 
### Result

emobiqApp.js?53:4456 ASP.NET_SessionId=afnllmm0512f1o01gxeuqrbp;UserBranch=16;LegacyUI=0;Locale=Culture=en-US&TimeZone=GMTM0800A;CompanyID=mydemo;.ASPXAUTH=49FCD47815A0C8AB42A759F7075F8CBC1300C95DE035B43E221BD674DE6FDD50E025F9145B9F2D30B4799B2596408DD6AE10EB0D215CD0F8197C8410928F23ACD93A6C001F14865E0766484A5A4F6CC880C2AA03DEBFE9C823D639D65E8C304E6D5ACD96FAF6F2C34F5D5A4C6F25C1219B2E341128C98CD6327C2DF9B2351BEBC85E96E2

![](../../../../document/function/Dataset/acumaticaCall/acumaticaCall-result-1.png?raw=true)

### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A