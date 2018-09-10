# getLocation

### Description

Get the current location details (GPS coordinate) of the device.

### Flowchart

- N/A

### Input / Parameters

| No | Name | Description | Data Type | Required | Example |
| ------ | ------ | ------ |------ | ------ | ------ |
| 1 | timeout | Connection time out period in millisecond | Integer | Yes | 1000, 2000, ...
| 2 | enableHighAccuracy | Enable High Accuracy | Boolean | No |

### Scenario / Use Case

The user want to detect the current location of mobile device.

### Step

1. Call the function. <br />
    timeout: 30000 (connection timeout after 30 seconds)
    enableHighAccuracy: true

    ![](getLocation1.png?raw=true)
    
2. In callback, add a console -> input function to view the result

    ![](getLocation2.png?raw=true)
    
### Result

User will see the result below in console: <br />
__{__ latLng: "1.4369448999999999,103.84171429999999", lat: 1.4369448999999999, long: 103.84171429999999, latitude: 1.4369448999999999, longitude: 103.84171429999999, __…}__

### Video

- N/A
<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A