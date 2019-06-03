# sc_carriage

### Description

Carriage Return (RF \r) commands a printer, or other output system such as the display of a system console, to move the position of the cursor to the first position on the same line.

### Flowchart

- N/A 

### Input / Parameters

- N/A

### Scenario / Use Case

The user wants to move the position of the cursor to the first position on the same line after a string.

### Step

1. Call the function "SetComponentValue" in the button and put in the following value. <br>
component: Memo <br>
value: "concat" function <br>

2. Inside the concat function, add value in string1 and call the function "sc_carriage" in string2. <br/>
    
    ![](../../../../document/function/SpecialCharacter/sc_carriage/sc_carriage-step-1.png?raw=true)
 
### Result
After the user click the button, the string "ABCD" will be populated in the memo. We can see that the cursor has been move to the first position.
 
 ![](../../../../document/function/SpecialCharacter/sc_carriage/sc_carriage-result-1.png?raw=true)
 
### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A