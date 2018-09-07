# encrypt


### Description

Convert information or data into a code.

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required | Example |
| ------ | ------ | ------ |------ | ------ |
| 1 | type |  Advanced Encryption Standard. | String | No | aes and aes256 |
| 2 | key | The key you want to encrypt. | String | Yes |
| 3 | iv | An initialization vector (IV) is an arbitrary number that can be used along with a secret key for data encryption. | Integer | Yes |
| 4 | value | The value need to be encrypt. | String | Yes |

### Scenario / Use Case

The user wants encrypt the data into code.

### Step

1. Call the function "encrypt" and define the value for type, key, iv and value.<br>
    type: aes256<br />
    key: sw234<br />
     iv: 16<br />
    value: 12121212<br />
    
    ![](encrypt-step-1.png?raw=true)

### Result

U2FsdGVkX1/urYvHdAM71G0H/+wOf7+04Q3JqqIjQ2g=

### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A