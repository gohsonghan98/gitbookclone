# generateBarcode

### Description

Create a a machine-readable code in the form of numbers and a pattern of parallel lines of varying widths, printed on a commodity and used especially for stock control.

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required | Example |
| ------ | ------ | ------ |------ | ------ |
| 1 | type | Type of barcode. |  | No  | <href><https://www.scandit.com/types-barcodes-choosing-right-barcode/>
| 2 | fontSize |  Size of the font. |  | No  |
| 3 | height | Height of the barcode. | Number | Yes  |
| 4 | width | Width of the barcode.  | Number | Yes  |
| 5 | value | Value of barcode.  | String | Yes |

### Scenario / Use Case

The user wants to generate a barcode.

### Step

1. Call the function "setComponentValue" and set the value for component.
   <br>
   component: imgQR<br/>
  
    ![](../../../../document/function/Conversion/generateBarcode/generateBarcode-step-1.png?raw=true)

2. Call the function "generateBarcode" and set the value for barcode.
   <br>
   height : 200 <br />
   width : 200 <br />
   value : aaa
   
   ![](../../../../document/function/Conversion/generateBarcode/generateBarcode-step-2.png?raw=true)
   
   ![](../../../../document/function/Conversion/generateBarcode/generateBarcode-step-3.png?raw=true)
   
3. Add a console for display the response from     console.
   
   ![](../../../../document/function/Conversion/generateBarcode/generateBarcode-step-4.png?raw=true)
 
### Result

   ![](../../../../document/function/Conversion/generateBarcode/generateBarcode-result-1.png?raw=true)
   
   ![](../../../../document/function/Conversion/generateBarcode/generateBarcode-result-2.png?raw=true)
   
### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A