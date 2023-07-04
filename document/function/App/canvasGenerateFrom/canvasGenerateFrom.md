# canvasGenerateFrom

## Description

Convert a file data to a canvas, canvas are mainly used for printing.

## Input / Parameter

| Name | Description | Data Type | Default | Options | Required |
| ------ | ------ | ------ | ------ | ------ | ------ |
| type | The data type of the file to be converted. | String | base64 | base64 | No |
| value | The data of the file to be converted. | Any | - | - | Yes | 
| fileType | The type of file to be converted. | String | image | image, pdf | No | 
| documentSize | If the 'fileType' is 'pdf', this parameter is used to scale the size appropriately. | String / Number | - | a4, {Any  Number} | No | 
<!-- | callback | When the function was triggered successfully. | Function List | No | 
| errorCallback | When the function trigger failed successfully. | Function List | No | -->

## Output

| Description | Output Type |
| ------ | ------ |
| Returns true if the canvas was generated, returns false otherwise. | Boolean |

## Callback?

Display and explain the callbacks available for the function.

Example below:

### successCallback

Explain what this callback is for?

| Description | Output Type |
| ------ | ------ |
| Returns the base64 value | Object |

#### Object

| Key | Description | Output Type |
| ------ | ------ | ------ |
| filePath | The base64 value. | String |

## Video

Coming Soon.

<!-- Format: [![Video]({image-path}?raw=true)]({url-link}) -->

## Example

<!-- Share a scenario, like a user requirements. -->

### Steps

Coming Soon.

<!-- Show the steps and share some screenshots.

1. .....

Format: ![]({image-path}?raw=true) -->

### Result

Coming Soon.

<!-- Explain the output.

Format: ![]({image-path}?raw=true) -->

## Links
