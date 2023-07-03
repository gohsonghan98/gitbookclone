# valueFromURL

## Description

Get the value of a URL parameter.

## Input / Parameter

| Name | Description | Input Type | Default | Options | Required |
| ------ | ------ | ------ | ------ | ------ | ------ |
| url | The Uniform Resource Locator. | String | - | - | Yes |
| parameter | A URL parameter whose value is set dynamically in a page's URl. | String | - | - | Yes |

## Output

### Default Output

| Description | Output Type |
| ------ | ------ |
| The URL parameter specified. | String |

## Video

Coming Soon.

## Example

The user wants to get the value of parameter "appID" in a URL. 

### Steps

1. Call the function. <br>
<b>url</b>: https://emobiq.com/edit/?appid=documentationTesting#/design <br />
<b>parameter</b>: appid <br />

    ![](../../../../document/function/Browser/valueFromURL/valueFromURL-step-1.png?raw=true)

### Result

The console returns the value "documentationTesting", which is the appID for the URL.

## Links