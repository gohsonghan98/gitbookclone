# canvasToDataURL

### Description

Convert the value in signature component to dataURL eg data:__[__&lt;mediatype&gt;__]__[_;base64_]_,&lt;data&gt; 

### Flowchart

- N/A

### Input / Parameters

| No | Name | Description | Data Type | Required | Example |
| ------ | ------ | ------ |------ | ------ | ------ |
| 1 | canvas | The name of signature component. | String | Yes | 

### Scenario / Use Case

The user want get the value of signature component and send to the server for processing.

### Step

1. Find the signature component. 

    ![](canvasToDataURL-step-1.png?raw=true)
    

2. Draw a signature component "Signature",  a button "canvasToDatURL".

    ![](canvasToDataURL-step-2.png?raw=true)
    

3. Call the function by adding a console -> canvasToDataURL in button event.

    ![](canvasToDataURL-step-3.png?raw=true)
    
### Result

In the console of browser, user can see the dataURL of signature component.

![](canvasToDataURL-result-1.png?raw=true)

### Video

- N/A
<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A