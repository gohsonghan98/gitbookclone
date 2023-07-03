# canvasGenerate

### Description

Generate a new canvas based on an existing canvas, canvas are mainly used for printing.

### Input / Parameter

| Name | Description | Data Type | Default | Options | Required |
| ------ | ------ | ------ | ------ | ------ | ------ |
| canvas | An existing canvas to be copied over to the new canvas. | Canvas | - | - | No |
| canvasWidth | Width of the new canvas. | Number | 300 | - | No | 
| canvasHeight | Height of the new canvas. | Number | 300 | - | No | 
| extra | Additional data to be used in the callbacks. | Any | - | - | No | 
| callback | When the function was triggered successfully. | Function List | - | - | No | 
| errCallback | When the function trigger failed successfully. | Function List | - | - | No | 

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