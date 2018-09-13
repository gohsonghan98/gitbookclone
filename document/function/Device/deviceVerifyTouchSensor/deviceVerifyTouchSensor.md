
# deviceVerifyTouchSensor

### Description

Verify fingerprint that stored in mobile device.

### Flowchart

- N/A

### Input / Parameters

| No | Name | Description | Data Type | Required |
| ------ | ------ | ------ |------ | ------ |
| 1 | key | Key in the device keychain | String | Yes |
| 2 | message | Message to display in fingerprint dialog | String | Yes |


### Scenario / Use Case

The user want verify fingerprint in their device and display the password in dialog box.

### Step

1. Call the deviceVerifyTouchSensor function in a button event.

    ![](deviceVerifyTouchSensor-step-1.png?raw=true)

2. In callback, add infoDialog function. 

    ![](deviceVerifyTouchSensor-step-2.png?raw=true)
    
### Result

Fingerprint authentication will be prompted with message we provided. <br />
![](deviceVerifyTouchSensor-result-1.png?raw=true)

Fingerprint recognized. <br />
![](deviceVerifyTouchSensor-result-2.png?raw=true)

The password "ABC" will be shown. <br />
![](deviceVerifyTouchSensor-result-3.png?raw=true)
### Video

- N/A
<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- Prerequisite: You must know how to use deviceAddTouchSensor function.
- The mobile device must have touch sensor and user must setup the fingerprint in their device settings.