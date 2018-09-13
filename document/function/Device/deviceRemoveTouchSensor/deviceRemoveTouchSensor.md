# deviceRemoveTouchSensor

### Description

Remove touch sensor for mobile device.


### Flowchart

- N/A

### Input / Parameters

| No | Name | Description | Data Type | Required |
| ------ | ------ | ------ |------ | ------ |
| 1 | key | Key in the device keychain | String | Yes |

### Scenario / Use Case

The user want remove specific key of touch sensor in their device.

### Step

1. Call the deviceRemoveTouchSensor function in a button event, define key to remove.

    ![](../../../../document/function/Device/deviceRemoveTouchSensor/deviceRemoveTouchSensor-step-1.png?raw=true)

2. In callback, add infoDialog function. 

    ![](../../../../document/function/Device/deviceRemoveTouchSensor/deviceRemoveTouchSensor-step-2.png?raw=true)

### Result

![](../../../../document/function/Device/deviceRemoveTouchSensor/deviceRemoveTouchSensor-result-1.png?raw=true)

### Video

- N/A
<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- Prerequisite: You must know how to use deviceAddTouchSensor function.
- The mobile device must have touch sensor and user must setup the fingerprint in their device settings.