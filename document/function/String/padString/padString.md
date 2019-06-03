# padString

### Description

This function returns a padded string (add padding to the original string) with a specified maximum length. No action is taken if the length of original string exceeds the maximum length. The user can specify the position of the original string (left, right or center).

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required | Example | 
| ------ | ------ | ------ |------ | ------ | ------ |
| 1 | string | Character, number and words. | String | Yes| - |
| 2 | len | Maximum length of the return string.  | Integer  | Yes | - |
| 3 | type | Postion of the original string in the return padded string. | String  | Yes | left, center or right |
| 4 | char | Optional string of one or more characters to use as padding. | String | No | - |

### Scenario / Use Case

The user wants to add padding to a string with maximum length of 10, with the original string at center.
</br>

### Step

1. Call the function.<br/>
    string: AB<br />
    len: 10<br />
    type: center<br />
        
   ![](../../../../document/function/String/padString/padString-step-1.png?raw=true)

### Result

 ![](../../../../document/function/String/padString/padString-result-1.png?raw=true)
 
 (4 spaces added on both of the left & right of "AB", total length of the string is now 10.)

### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

 The user also can set the parameter as:<br/>
 string: AB<br>
 len: 10<br />
 type: center<br />
 char: aa<br />
    
  ![](../../../../document/function/String/padString/padString-step-2.png?raw=true)
 
 
 Result:
 
  ![](../../../../document/function/String/padString/padString-result-2.png?raw=true)
  
  (In this result, you can see that the char "aa" will used as padding character and display on both side of the string "AB" with the total length is 10. Do note that "aa" here considered as length = 1.)