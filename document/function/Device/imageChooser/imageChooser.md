# imageChooser

### Description

Select image from phone storage.

### Flowchart

- N/A

### Input / Parameters

| No | Name | Description | Data Type | Required | Example |
| ------ | ------ | ------ |------ | ------ | ------ |
| 1 | quality | Quality of the saved image, expressed as a range of 0-100, where 100 is typically full resolution with no loss from file compression. | Integer | Yes | 50
| 2 | height | Height in pixels to scale image. Must be used with width. Aspect ratio remains constant. | Integer | No |
| 3 | width | Width in pixels to scale image. Must be used with height. Aspect ratio remains constant. | Integer | No |

### Scenario / Use Case

The user want display the image by choosing it from gallery/phone storage.

### Step

1. Draw a image component "Image653", a button component "imageChooser". 

    ![](../../../../document/function/Device/imageChooser/imageChooser-step-1.png?raw=true)
    
2. In button event, add imageChooser function as below: 

    ![](../../../../document/function/Device/imageChooser/imageChooser-step-2.png?raw=true)

3. In callback, add a setComponentValue function by giving component as "Image653" & value as an input.

    ![](../../../../document/function/Device/imageChooser/imageChooser-step-3.png?raw=true)

### Result

The image choosen will be displayed in image component.
![](../../../../document/function/Device/imageChooser/imageChooser-result-1.png?raw=true)

### Video

- N/A
<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A