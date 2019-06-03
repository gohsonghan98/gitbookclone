# valueFromURL

### Description

Get the value of parameter in URL.

### Flowchart

- N/A

### Input / Parameters

| No | Name | Description | Data Type | Required |
| ------ | ------ | ------ |------ | ------ |
| 1 | url | Uniform Resource Locator | String | Yes | 
| 2 | parameter | URL Parameters are parameters whose values are set dynamically in a page's URL | String | Yes |


### Scenario / Use Case

The user want to get value of parameter "appID" in a given URL. <br />


### Step

1. Call the function. <br>
<b>url</b>: https://emobiq.com/edit/?appid=documentationTesting#/design <br />
<b>parameter</b>: appid <br />

    ![](../../../../document/function/Browser/valueFromURL/valueFromURL-step-1.png?raw=true)

### Result

The console return the value "documentationTesting", which is the appID for the URL.

### Video

- N/A
<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes
- N/A