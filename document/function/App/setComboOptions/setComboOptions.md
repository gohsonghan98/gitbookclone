# setComboOptions

### Description

Set the value / options for combo box.

### Flowchart

- N/A

### Input / Parameters

| No | Name | Description | Data Type | Required | Example |
| ------ | ------ | ------ |------ | ------ | ------ |
| 1 | combo | The name of the component. | String | No __*__ | 
| 2 | comboId | The id of the component | String | No __*__ |
| 3 | data | The list of data (an array of object) | Array/JsonArray | Yes | __[__ <br /> {__"code":"1","name":"abc"__}__, __{__"code":"2","name":"dfe"__} <br /> __]__
| 4 | valueField | The id of the component | String | Yes |
| 5 | displayField | The id of the component | String | Yes |

__\* Note:__ Either No 1 or No 2 must have value in order for this function to work.

### Scenario / Use Case

The user want to make a not visible component to visible.

### Step

1. Draw a combo box "ComboBox617", a button "setComboOptions".

    ![](setComboOptions-step-1.png?raw=true)
    

2. Call the function

    ![](setComboOptions-step-2.png?raw=true)
    

3. Populate an array into data parameter by adding "toArray" & "toObject" functions.

    ![](setComboOptions-step-3.png?raw=true)
    

4. Define the value field & display field.

    ![](setComboOptions-step-4.png?raw=true)
    
### Result

The combo box "ComboBox617" have the display values of "abc" & "dfe" & the value of "abc is 1, value of "dfe" is 2.

![](setComboOptions-result-1.png?raw=true)

### Video

- N/A
<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A