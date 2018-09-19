# deviceAddTouchSensor

### Description

Add touch sensor for mobile device.


### Flowchart

- N/A

### Input / Parameters

| No | Name | Description | Data Type | Required |
| ------ | ------ | ------ |------ | ------ |
| 1 | key | Key in the device keychain | String | Yes |
| 2 | password | Used to create credential string for encrypted token| String | Yes |

### Scenario / Use Case

The user want add touch sensor to their device.

### Step

1. Call the deviceAddTouchSensor function in a button event.

    ![](../../../../document/function/Device/deviceAddTouchSensor/deviceAddTouchSensor-step-1.png?raw=true)

2. In callback, add infoDialog function. 

    ![](../../../../document/function/Device/deviceAddTouchSensor/deviceAddTouchSensor-step-2.png?raw=true)

### Result

Mobile will ask for fingerprint authentication. <br />
![](../../../../document/function/Device/deviceAddTouchSensor/deviceAddTouchSensor-result-1.png?raw=true)

Touch on touch sensor of device, fingerprint wil be recognized. <br />
![](../../../../document/function/Device/deviceAddTouchSensor/deviceAddTouchSensor-result-2.png?raw=true)

Info dialog will be prompted.<br />
![](../../../../document/function/Device/deviceAddTouchSensor/deviceAddTouchSensor-result-3.png?raw=true)

### Video

- N/A
<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- Prerequisite: You must know how to use deviceHasTouchSensor function.
- The mobile device must have touch sensor and user must setup the fingerprint in their device settings.