# watchPosition

### Description

Return the location details (GPS coordinate) of the device if detect changes.

### Flowchart

- N/A

### Input / Parameters

| No | Name | Description | Data Type | Required | Example |
| ------ | ------ | ------ |------ | ------ | ------ |
| 1 | timeout | Connection time out period in millisecond | Integer | Yes | 1000, 2000, ...
| 3 | enableHighAccuracy | Enable High Accuracy | Boolean | No |
| 3 | enableHighAccuracy | Enable High Accuracy | Boolean | No |

### Scenario / Use Case

The user want to get the current location of mobile device if the location changed.

### Step

1. Call the function. <br />
    timeout: 30000 (connection timeout after 30 seconds)<br />
    maximumAge: 100
    enableHighAccuracy: true

    ![](watchPosition-step-1.png?raw=true)
    
2. In callback, add a console -> input function to view the result.

    ![](watchPosition-step-2.png?raw=true)
    
### Result

User will see the result below in console (the latlng will have different value): 

![](watchPosition-result-1.png?raw=true)

### Video

- N/A
<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A