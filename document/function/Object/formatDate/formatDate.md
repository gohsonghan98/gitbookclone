# FormatDate

### Description

Set format for the date.

### Flowchart

- N/A 


### Input / Parameters

| No | Name | Description | Data Type | Required | Example |
| ------ | ------ | ------ |------ | ------ | ------ |
| 1 | date | A date value | Date | Yes |
| 2 | format | The way in which something is arranged or set out. | Date | Yes | Y.m.d H:m:s (**list of format) |

### Scenario / Use Case

User want to change the date format.
</br>

### Step

1. Call the function "formatDate"
 
   ![](../../../../document/function/Object/formatDate/formatDate-step-1.png?raw=true)
    
2. Call the function "dbDate"  and set the         format
   <br>
   format : Y.m.d H:m:s <br />
   withTime: true<br>
    
   ![](../../../../document/function/Object/formatDate/formatDate-step-2.png?raw=true)

### Result

2018.08.28 14:08:50

### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A