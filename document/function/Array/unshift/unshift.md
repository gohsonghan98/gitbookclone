# unshift

## Description

Adds new elements to the beginning of an array and returns the updated array.

## Input / Parameter

| Name | Description | Input Type | Default | Options | Required |
| ------ | ------ | ------ | ------ | ------ | ------ |
| var | The name of the array. | String | - | - | Yes |
| data | ? | String | - | - | Yes |
| value | Element to be added to the the array. | String | - | - | Yes |

## Output

### Default Output

| Description | Output Type |
| ------ | ------ |
| The updated array with the items added. | Array |

## Video

Coming Soon.

## Example

The user wants to add new items to the beginning of an array.

### Steps

1. Call the function "newArray" and "push" (We assumed that the new array and the value of array have been created.)
   </br>
   var: listOfFruits<br />
   value : Apple<br>
   value : Orange<br>    
   
   ![](../../../../document/function/Array/unshift/unshift-step-1.png?raw=true)
   
   ![](../../../../document/function/Array/unshift/unshift-step-2.png?raw=true)
   
   ![](../../../../document/function/Array/unshift/unshift-step-3.png?raw=true)

2. Call the function "unshift" and set the value.
   </br>
   var: listOfFruits<br />
   value: Papaya<br>
 
   ![](../../../../document/function/Array/unshift/unshift-step-4.png?raw=true)
   
3. Add a console for display the input.

   ![](../../../../document/function/Array/unshift/unshift-step-5.png?raw=true)

### Result

The updated array with the new elements added will be returned. In this example, the return is ["Papaya", "Apple", "Orange"].

## Links