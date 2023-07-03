#  sendMail

## Description

Send an email through the app.

## Input / Parameter

| Name | Description | Input Type | Default | Options | Required |
| ------ | ------ | ------ | ------ | ------ | ------ |
| config | The configuration of the email to be sent. | Object | - | - | Yes |
| from | The name of the sender. | Object | - | - | Yes |
| to | The name of the recipient. | Array | - | - | Yes |
| cc | The carbon copy. | Array | - | - | No |
| bcc | The blind carbon copy. | Array | - | - | No |
| data | The contents of the email. | Object | - | - | Yes |
| attachment | The file(s) to be attached. | String/Array? | - | - | No |

## Output

### Default Output

| Description | Output Type |
| ------ | ------ |
| Returns a the email structure. | String |

## Video

Coming Soon.

## Example

The user wants to send an email via the app.

### Steps

1. Call the sendMail function, add toObject function in "config" parameter as below:

    ![](../../../../document/function/App/sendMail/sendMail-step-1.png?raw=true)

2. For "from" paremeter, add toObject with "email" & "name".

    ![](../../../../document/function/App/sendMail/sendMail-step-2.png?raw=true)

3. For "to" paremeter, add toArray function then toObject funtion.

    ![](../../../../document/function/App/sendMail/sendMail-step-3.png?raw=true)

    Add fields "email" & "name".

    ![](../../../../document/function/App/sendMail/sendMail-step-5.png?raw=true)

4. For "cc" paremeter, add toArray function then toObject funtion.
   
    ![](../../../../document/function/App/sendMail/sendMail-step-4.png?raw=true)

    Add fields "email" & "name".

    ![](../../../../document/function/App/sendMail/sendMail-step-6.png?raw=true)

5. For "data" paremeter, add toObject function then add fields "subject" "body". 

    ![](../../../../document/function/App/sendMail/sendMail-step-7.png?raw=true)

### Result

Email Received:
![](../../../../document/function/App/sendMail/sendMail-result-1.png?raw=true)

## Links
