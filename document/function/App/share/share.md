# share

## Description

Share the information from an app to an external application.

## Input / Parameter

| Name | Description | Input Type | Default | Options | Required |
| ------ | ------ | ------ | ------ | ------ | ------ |
| subject | The subject of the information. | String | - | - | No |
| message | The message to be shared. | String | - | - | No | 
| url | The url to be shared. | String | - | - | Yes | 
| files | Array of files. | String / Array? | - | - | Yes |
| chooserTitle | Choose the title of the dialog. | String | - | - | Yes |
| appPackageName | The name of the package. | String | - | - | Yes |
| iPadCoordinates | The coordinates of iPad popup. | String | - | - | Yes |
| callback | Function to carry out if information is successfully shared. | functionList | - | - | No |
| errorCallback | Function to carry out if information is not shared successfully. | functionList | - | - | No |

## Output

### Default Output?

| Description | Output Type |
| ------ | ------ |
| Returns the base64 value | String |

```js
    {
        "filePath": "{filePath}"
    }
```

### Parameter Output: {parameter-name}

#### successCallback?

#### errorCallback?

## Video

Coming Soon.

## Example

The user wants to share information from the app to an external application.

### Steps

Coming Soon.

### Result

Coming Soon.

## Links
