# hashingFunction

### Description

A hash function is any function that can be used to map data of arbitrary size onto data of a fixed size. The values returned by a hash function are called hash values, hash codes, digests, or simply hashes.

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required | Example |
| ------ | ------ | ------ |------ | ------ | ----- |
| 1 | type |  Cryptographic hash function | String | Yes | md5 and sha256 |
| 2 | value | Character and words. | String | Yes |

### Scenario / Use Case

The user wants to transform a string into a 128-bit hash value by using md5 hash function.

### Step

1. Call the function.<br>
	type: md5<br>
   value: abcd<br />
    
    ![](../../../../document/function/String/hashingFunction/hashingFunction-step-1.png?raw=true)

### Result

e2fc714c4727ee9395f324cd2e7f331f

### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A