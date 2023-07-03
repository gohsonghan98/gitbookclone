#  pullToRefresh

## Description

Pull a panel component to trigger a screen to reload.

## Input / Parameters

| Name | Description | Input Type | Default | Options | Required |
| ------ | ------ | ------ | ------ | ------ | ------ |
| class | The style class to be refreshed.? | String | - | - | Yes |
| maxTime | The maximum time to load the screen. | Integer | - | - | No |

## Output

### Default Output

| Description | Output Type |
| ------ | ------ |
| Checks if the screen has reloaded. | Boolean |

## Video

Coming Soon.

## Example

The user wants to refresh the screen by pulling a panel component.

### Steps

1.  In page event "Load",  add pullToRefresh function.

    ![](../../../../document/function/App/pullToRefresh/pullToRefresh-step-1.png?raw=true)

2.  In onRefresh, add an infoDialog.

    ![](../../../../document/function/App/pullToRefresh/pullToRefresh-step-2.png?raw=true)

3.  Draw a panel and set the background to red.

    ![](../../../../document/function/App/pullToRefresh/pullToRefresh-step-3.png?raw=true) 

4.  Define "pull" for Style Class on Panel Inspector.

    ![](../../../../document/function/App/pullToRefresh/pullToRefresh-step-4.png?raw=true)

### Result

After user pull on red color panel, the pullToRefresh function will be triggered.
![](pullToRefresh-result-5.png?raw=true)

## Links
