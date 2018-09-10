#  pullToRefresh

### Description

Pull the panel and reload the screen.

### Flowchart

- N/A

### Input / Parameters

| No | Name | Description | Data Type | Required | 
| ------ | ------ | ------ |------ | ------ | 
| 1 | class | Style class. | String | Yes | 
| 2 | maxTime | Maximum time. | Integer | No | 


### Scenario / Use Case

The user want do some operations / processing by pulling the panel.

### Step

1.  In page event "Load",  add pullToRefresh function.

    ![](pullToRefresh1.png?raw=true)

2.  In onRefresh, add infoDialog.

    ![](pullToRefresh2.png?raw=true)

3.  Draw a panel and set the background to red.

    ![](pullToRefresh3.png?raw=true) 

4.  Define "pull" for Style Class on Panel Inspector.

    ![](pullToRefresh4.png?raw=true)
    
### Result

After user pull on red color panel, the pullToRefresh function will be triggered.
![](pullToRefresh5.png?raw=true)

### Video

- N/A

### Notes

- N/A