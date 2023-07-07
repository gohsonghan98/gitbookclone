# captureImage

### Description

Activates the camera of the mobile device to capture image.

### Flowchart

- N/A

### Input / Parameters

| No | Name | Description | Data Type | Required | Example |
| ------ | ------ | ------ |------ | ------ | ------ |
| 1 | quality | Quality of the saved image, expressed as a range of 0-100, where 100 is typically full resolution with no loss from file compression. | Integer | Yes | 50
| 2 | height | Height in pixels to scale image. Must be used with width. Aspect ratio remains constant. | Integer | No |
| 3 | width | Width in pixels to scale image. Must be used with height. Aspect ratio remains constant. | Integer | No |

### Scenario / Use Case

The user want to take photo using mobile device and view the photo in the image component.

### Step

1. Draw a image component "Image653", a button "captureImage"
  
    ![](../../../../document/function/Device/captureImage/captureImage-step-1.png?raw=true)
    
2. Call the function captureImage in the button.

    ![](../../../../document/function/Device/captureImage/captureImage-step-2.png?raw=true)

3. In callback, call setComponentValue to set the image to the image component.

    ![](../../../../document/function/Device/captureImage/captureImage-step-3.png?raw=true)
    
### Result

The image captured will be shown in the image component.

![](../../../../document/function/Device/captureImage/captureImage-result-1.png?raw=true)

### Video

- N/A
<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- User must build the app first before they can test on this function.