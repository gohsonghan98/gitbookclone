# bbCodeToCanvas

## Description

Generate a canvas by following a specific format, canvas are mainly used for printing.

## Input / Parameter

| Name | Description | Data Type | Default | Options | Required |
| ------ | ------ | ------ | ------ | ------ | ------ |
| text | The text with a specific format to be drawn in the canvas. See Text Format after this table. | String | - | - | No |
| font | The name of the font to be used. | String | monospace | monospace, ocrb | No | 
| size | The size of the font to be used with the suffix 'px' for pixel. | String | 23px | - | No | 
| canvasWidth | The width of the canvas. | Number | 576 | - | No | 
| marginTop | The margin top value of the canvas. | Number | 0 | - | No | 
| marginLeft | The margin left value of the canvas. | Number | 0 | - | No | 
| marginRight | The margin right value of the canvas. | Number | 0 | - | No | 
| marginBottom | The margin bottom value of the canvas. | Number | 0 | - | No | 

Text Format
- Bold: ```[b]```The text to apply bold.```[/b]```
- Italic: ```[i]```The text to apply italic.```[/i]```
- Image: ```[img x={number} y={number} width={number} height={number}]```The image to be rendered, a base64 or url.```[/img]```
- Font: ```[font={monospace|ocrb}]```The text to apply the font.```[/font]```
- Size: ```[size={number}]```The text to apply the size.```[/size]```
- Linespace: ```[linespace={number}]```The text to apply the linespace.```[/linespace]```
- Alignment: ```[alignment={left|right}]```The text to apply the alignment, where it will start.```[/alignment]```
- Underline: ```[u]```The text to apply underline.```[/u]```
- Strikethrough: ```[s]```The text to apply strikethrough.```[/s]```

See 'setPrintStyle' function to simplify the formatting.

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