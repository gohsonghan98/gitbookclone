
# barcodeScanner

### Description

Activate barcode scanner using camera of device.

### Flowchart

- N/A

### Input / Parameters

| No | Name | Description | Data Type | Required |
| ------ | ------ | ------ |------ | ------ |
| 1 | showFlipCameraButton | Show flip camera button. Supported on iOS and Android | Boolean | No |
| 2 | showTorchButton | Show torch button. Supported on iOS and Android | Boolean | No |
| 3 | torchOn | Launch with the torch switched on (if available). Supported on Android only. | Boolean | No |
| 4 | prompt | Prompt text. Supported on Android only. | String | No |
| 5 | resultDuration | Display scanned text for X ms. 0 suppresses it entirely, default 1500. Supported on Android only. | Number | No |

### Scenario / Use Case

The user want scan barcode and display in a dialog.

### Step

1. Call the barcodeScanner function in a button event.

    ![](barcodeScanner-step-1.png?raw=true)

2. In callback, add infoDialog function. 

    ![](barcodeScanner-step-2.png?raw=true)
    
### Result

When press on button, the barcode scanner will be activated. <br />
![](barcodeScanner-result-1.png?raw=true)

After scanned the barcode, the value will be displayed in a dialog box. <br />
![](barcodeScanner-result-2.png?raw=true)

### Video

- N/A
<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A