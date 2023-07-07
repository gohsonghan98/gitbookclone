# Component Method


### Description

To peform InsertBy, DeleteBy, UpdateBy functions to the local table's data. 

### Flowchart

- N/A

### Input / Parameters

| No | Name | Description | Data Type | Required |
| ------ | ------ | ------ |------ | ------ |
| 1 | component | Local table Name | String | yes |
| 2 | component Id | - | String | No |
| 3 | method | method to execute changes to local table | String | yes |
| 4 | arguements | customized parameter to allow the method to work | String | yes |



### Scenario / Use Case

The user wants delete a row the data inside the local table. 

### Step
1. make sure local table is added to Services, and consist of some data.
 
     ![](../../../../document/function/App/componentMethod/componentMethod-Step-1.png?raw=true)

2. Call Function "ComponentMethod"
 
     ![](../../../../document/function/App/componentMethod/componentMethod-Step-2.png?raw=true)
     
3. fill up the function

     ![](../../../../document/function/App/componentMethod/componentMethod-Step-3.png?raw=true)
     
4. run the function and result is the row with ID : ABC123 is deleted 

![](../../../../document/function/App/componentMethod/componentMethod-Step-4.png?raw=true)


### Result
-
### Video

- N/A

### Notes

- You can use this component method to edit the data in the localtable.