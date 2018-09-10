# padString


### Description

Set the type of alignment for a string.

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required | Example | 
| ------ | ------ | ------ |------ | ------ |
| 1 | string | Character, number and words. | String | Yes|
| 2 | len | Length  | Integer  | Yes | 
| 3 | type | Alignment type. | String  | Yes | left, center and right |
| 4 | char | Single character. | String | Yes |

### Scenario / Use Case

The user wants to centralize a string of length 10.
</br>

### Step

1. Call the function.<br/>
    string: AB<br />
    len: 10<br />
    type: center<br />
        
 ![](padString-step-1.png?raw=true)

### Result

 ![](padString-result-1.png?raw=true)

### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

 The user also can set the alignment as:<br/>
 string: AB<br>
 len: 10<br />
 type: center<br />
 char: aa<br />
    
 ![](padString-step-2.png?raw=true)
 
 
 Result:
 
  ![](padString-result-2.png?raw=true)
  
  (In this result, you can see that the char"aa" will display at both side of the string "AB"with the total length is 10. )