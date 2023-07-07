# decrypt

### Description

The conversion of encrypted data into its original form.

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required | Example |
| ------ | ------ | ------ |------ | ------ | ----- |
| 1 | type |  Advanced Encryption Standard. | String | No | aes / aes256 |
| 2 | key | The key you want to decrypt. | String | Yes |
| 3 | iv | An initialization vector (IV) is an arbitrary number that can be used along with a secret key for data encryption. | Integer | Yes |
| 4 | value | The value need to be decrypt. | String | Yes |

### Scenario / Use Case

The user wants decrypt the code into data.

### Step

1. Call the function "decrypt" and define the value for type, key,    iv and value.<br>
   type: aes256<br />
   key: sw234<br />
   iv: 2<br />
   value: U2FsdGVkX19zGcohyGZ2fjig<br />
    
   ![](../../../../document/function/String/decrypt/decrypt-step-1.png?raw=true)

### Result

12121212

### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A