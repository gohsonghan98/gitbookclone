# canvasGenerateFrom

### Description

Convert a file data to a canvas, canvas are mainly used for printing.

### Input / Parameter

| Name | Description | Data Type | Default | Options | Required |
| ------ | ------ | ------ | ------ | ------ | ------ |
| type | The data type of the 'value'. | String | base64 | base64 | No |
| value | The data of the file. | Any | - | - | Yes | 
| fileType | The type of the file. | String | image | image, pdf | No | 
| documentSize | If the 'fileType' is 'pdf', this parameter is used to scale the size appropriately. | String / Number | - | a4, {Any  Number} | No | 
| callback | When the function was triggered successfully. | Function List | No | 
| errorCallback | When the function trigger failed successfully. | Function List | No | 

## Output

### Default Output

| Description | Output Type |
| ------ | ------ |
| If the canvas was generated. | Boolean |


| Description | Output Type |
| ------ | ------ |
| Contains the information below. | Object |

```js
    {
        "filePath": "{This contains the url.}",
        "fileName": "{}",
    }
```

### Parameter Output

#### yes

| Description | Output Type |
| ------ | ------ |
| If the component was animated. | Boolean |


| Description | Output Type |
| ------ | ------ |
| Contains the information below. | Object |

```js
    {
        "filePath": "{This contains the url.}",
        "fileName": "{}",
    }
```

#### errorCallback

## Video

Coming Soon.

## Example

Coming Soon.

### Steps

Coming Soon.

### Result

Coming Soon.

## Links