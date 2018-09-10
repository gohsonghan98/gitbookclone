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

1.  Call the function in the button event.

    ![](sendMail1.png?raw=true)
    
### Result

Email Received:
![](sendMail2.png?raw=true)

### Video

- sendMail2.mov

### Notes

- N/A