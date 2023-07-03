# canvasResize

### Description

Resize an existing canvas, canvas are mainly used for printing.

### Input / Parameter

| Name | Description | Data Type | Default | Options | Required |
| ------ | ------ | ------ | ------ | ------ | ------ |
| canvas | An existing canvas to be copied over to the new canvas. | Canvas | - | - | No |
| canvasWidth | Width of the new resized canvas. | Number | - | - | No | 
| canvasHeight | Height of the new resized canvas. | Number | - | - | No | 
| extra | Additional data to be used in the callbacks. | Any | - | - | No | 
| callback | When the function was triggered successfully. | Function List | - | - | No | 
| errorCallback | When the function trigger failed successfully. | Function List | - | - | No | 

## Output

### Default Output

| Description | Output Type |
| ------ | ------ |
| If the canvas was resized. | Boolean |


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