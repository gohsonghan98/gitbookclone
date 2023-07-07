# inactivityTimeout

## Description

Detect if a user is inactive/not using the mobile.

### Input / Parameters

| Name | Description | Input Type | Default | Options | Required |
| ------ | ------ | ------ | ------ | ------ | ------ |
| currentPageOnly | A snippet. | Boolean | - | - | Yes |
| timeout | The time limit that a user can stay idle for before being considered inactive. | Integer | - | - | Yes |
| callback | Functions to do after timeout. | functionList | - | - | Yes |

## Output

### Default Output

| Description | Output Type |
| ------ | ------ |
| Checks if a user is inactive. | Boolean |

### Parameter Output: {parameter-name}

#### yes??

| Description | Output Type |
| ------ | ------ |
| Contains the information below. | Object |

```js
    {
        "filePath": "{This contains the url.}",
        "fileName": "{}",
    }
```
## Video

Coming Soon.

## Example

The user wants to check the status when the screen goes to timeout.

### Steps

Coming Soon.

### Result

Coming Soon.

## Links
