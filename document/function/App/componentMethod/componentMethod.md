# Component Method


## Description

To perform InsertBy, DeleteBy or UpdateBy functions to insert, delete or update data in the local table respectively. 

## Input / Parameter

| Name | Description | Input Type | Default | Options | Required |
| ------ | ------ | ------ | ------ | ------ | ------ |
| component | The name of the local table. | String | - | - | Yes |
| componentId | The id of the local table. | String | - | - | No |
| method | The method to be used to execute the changes in the local table. | String | - | - | Yes |
| arguments | The data to be edited, such as a row in the local table. | String | - | - | Yes |

## Output

### Default Output

| Description | Output Type |
| ------ | ------ |
| The data in the local table is updated with the selected function. | - |

### Parameter Output: {parameter-name}

The parameter output of the function.

## Video

Coming Soon.

## Example

The user wants to delete a row of data inside the local table. 

### Steps

1. make sure local table is added to Services, and consist of some data.
 
     ![](../../../../document/function/App/componentMethod/componentMethod-Step-1.png?raw=true)

2. Call Function "componentMethod"
 
     ![](../../../../document/function/App/componentMethod/componentMethod-Step-2.png?raw=true)
     
3. Fill up the function

     ![](../../../../document/function/App/componentMethod/componentMethod-Step-3.png?raw=true)
     
4. Run the function and result is the row with ID : ABC123 is deleted 

     ![](../../../../document/function/App/componentMethod/componentMethod-Step-4.png?raw=true)
     
### Result

The row in the local table with id = 'ABC123' is deleted.

## Links
