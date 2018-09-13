# setCompoentFocus

### Description

Set focus on a component.

### Flowchart

- N/A

### Input / Parameters

| No | Name | Description | Data Type | Required |
| ------ | ------ | ------ |------ | ------ | 
| 1 | component | The name of the component | String | No __*__ | 
| 2 | componentId | The id of the component | String | No __*__ |
| 3 | selectAllText | Highlight all the words in component | Boolean | No |
| 4 | hideKeyboard | Display of keyboard | Boolean | No |

__\* Note:__ Either No 1 or No 2 must have value in order for this function to work.


### Scenario / Use Case

The user want to set focus on a component and highlight all the words in a component. For example highlighting all the word in a edit text.

### Step

1. Draw an edit text "txtTest", a button "setComponenFocus".

    ![](../../../../document/function/App/setCompoentFocus/setCompoentFocus-step-1.png?raw=true)
    
2. Call the function.

    ![](../../../../document/function/App/setCompoentFocus/setCompoentFocus-step-2.png?raw=true)

### Result

The words "aaa" in the edit text will be selected.

![](../../../../document/function/App/setCompoentFocus/setCompoentFocus-result-1.png?raw=true)

### Video

- N/A
<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- N/A