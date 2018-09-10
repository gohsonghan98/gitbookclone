#  convertImageToBase64

### Description

Convert the value in signature component to base64.

### Flowchart

- N/A

### Input / Parameters

| No | Name | Description | Data Type | Required | 
| ------ | ------ | ------ |------ | ------ | 
| 1 | image | The name of image component. | String | Yes | 

### Scenario / Use Case

The user get the value signature component in base64 format.

### Step

1. Draw a signature component "Signature", a button "canvasToImage". 

    ![](convertImageToBase64_1.png?raw=true)
    
2. Call the function in the button event, define defaultImage in image parameter.

    ![](convertImageToBase64_2.png?raw=true)

3. In callback, define a console-> input functions.

    ![](convertImageToBase64_3.png?raw=true)
    
### Result

After click on the button, the console show as base64 string:
![](convertImageToBase64_4.png?raw=true)

### Video

- N/A
<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A