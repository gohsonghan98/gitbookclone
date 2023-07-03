# animate

## Description

An animation lets a component gradually change from one style to another. 

## Input / Parameter

| Name | Description | Data Type | Default | Options | Required |
| ------ | ------ | ------ | ------ | ------ | ------ |
| component | Name of componnent to animate. | String | - | - | Partial (Yes if no 'componentId'.) |
| componentId | ID of the component to animate. | String | - | - | Partial (Yes if no 'component'.) | 
| type | Not applicable for now. | String | - | - | No | 
| startPositionY | Starting y-axis position of the animation. | Number | 0 | - | No | 
| endPositionY | Ending y-axis position of the animation. | Number | 0 | - | No | 
| rotationDegree | Rotation degree of the animation. | Number | 2 | - | No | 

## Output

### Default Output

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