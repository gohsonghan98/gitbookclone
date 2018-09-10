#  sendMail

### Description

Send in app email.

### Flowchart

- N/A

### Input / Parameters

| No | Name | Description | Data Type | Required | 
| ------ | ------ | ------ |------ | ------ | 
| 1 | config | The configuration of email. | Object | Yes | 
| 2 | from | The sender. | Object | Yes | 
| 3 | to | The recipient. | Array | Yes | 
| 4 | cc | The carbon copy. | Array | No | 
| 5 | bcc | The blind carbon copy. | Array | No | 
| 6 | data | The content of email. | Object | Yes | 
| 7 | attachment | The file attachment | String??? | No | 

### Scenario / Use Case

The user want to send an email via the app.

### Step

1. Call the sendMail function, add toObject function in "config" parameter as below:

    ![](sendMail-step-1.png?raw=true)

2. For "from" paremeter, add toObject with "email" & "name".

    ![](sendMail-step-2.png?raw=true)

3. For "to" paremeter, add toArray function then toObject funtion.

    ![](sendMail-step-3.png?raw=true)

    Add fields "email" & "name".

    ![](sendMail-step-5.png?raw=true)

4. For "cc" paremeter, add toArray function then toObject funtion.
   
    ![](sendMail-step-4.png?raw=true)

    Add fields "email" & "name".

    ![](sendMail-step-6.png?raw=true)

5. For "data" paremeter, add toObject function then add fields "subject" "body". 

    ![](sendMail-step-7.png?raw=true)
    
### Result

Email Received:
![](sendMail-result-1.png?raw=true)

### Video

- N/A

### Notes

- N/A