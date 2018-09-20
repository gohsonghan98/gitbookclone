# generateQRCode

### Description

Create a trademark for a type of matrix barcode. 

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required | Example |
| ------ | ------ | ------ |------ | ------ |
| 1 | type | Type of QR Code |  | Yes  | <href><http://www.qrcode.com/en/codes/>"
| 2 | value | Value for QR Code |  | Yes  |
| 3 | imageSize | Size of image | Number | Yes  |
| 4 | method | Method |  | Yes  |
| 5 | local | If the value is true, it will generate the code from mobile and otherwise it will generate from internet. | Boolean | No |
| 6 | extra |  |  | No | 

### Scenario / Use Case

The user wants to generate a QR Code.

### Step

1. Call the function.
   <br>
   type : qr <br />
   value : ABCD <br />
   imageSize : 200 <br />
   method : post <br />

   ![](../../../../document/function/Conversion/generateQRcode/generateQRcode-step-1.png?raw=true)
   
   ![](../../../../document/function/Conversion/generateQRcode/generateQRcode-step-2.png?raw=true)
   
2. Add a console for display the response from console.
    
   ![](../../../../document/function/Conversion/generateQRcode/generateQRcode-step-3.png?raw=true)
 
### Result
    
![](../../../../document/function/Conversion/generateQRcode/generateQRcode-result-1.png?raw=true)
   
![](../../../../document/function/Conversion/generateQRcode/generateQRcode-result-2.png?raw=true)
   
### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A