# Query  

### Description

A query is a request for data or information from a database table or combination of tables.

### Flowchart

- N/A 

### Input / Parameters

| No | Name | Description | Data Type | Required | Example |
| ------ | ------ | ------ |------ | ------ | ------ |
| 1 | dataset | Name of the dataset to be read in local table. | String | Yes |
| 2 | query | A request for data or information from a database table.  | String | Yes | <a href:></a> </a> https://www.javatpoint.com/mysql-queries</a>

### Scenario / Use Case

The user wants to update the data for table tbl_sqllite_customer by using the query.

### Step

1. Create the SQLiteTable in Services and fill     the info such as Name and fields. Call the function "insert" for insert data into table before you update.Define the dataset, set the toObject to dt and define code and name.
   <br>
   Name: tbl_sqllite_customer<br>
   fields: code and name<br>
   Dataset: tbl_sqllite_customer<br>
   dt: toObject<br>
   code: B<br>
   name: abc<br>
   name: aaa<br>
   code: 1111<br>
   
   ![](../../../../document/function/Dataset/query/query-step-1.png?raw=true)
   
   ![](../../../../document/function/Dataset/query/query-step-2.png?raw=true)
   
   ![](../../../../document/function/Dataset/query/query-step-3.png?raw=true)
   
2. Call the function "query" for update the data    and define the dataset and query.
   <br>
   dataset: tbl_sqllite_customer<br>
   query: UPDATE tbl_sqllite_customer SET code = 'A1' WHERE code='B'<br>
   
   ![](../../../../document/function/Dataset/query/query-step-4.png?raw=true)
   
3. Call the function "loadData" and define the     dataset.
   <br>
   dataset: tbl_sqllite_customer<br>
   
   ![](../../../../document/function/Dataset/query/query-step-5.png?raw=true)
   
 
### Result



### Video

- N/A

<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

insert

1. Call the function "insert" and define the       dataset and set the function "toObject" to       data & define the code and name.<br>( We        assumed you have created the SQLiteTable in     Services and fill the info such as Name and     fields. )
   <br>
   Dataset: tbl_sqllite_customer<br>
   dt: toObject<br>
   code: B<br>
   name: abc<br>
   name: aaa<br>
   code: 1111<br>
   
   ![](query-step-6.png?raw=true)
   
   ![](query-step-7.png?raw=true)
   
2. Call the function "loadData" and define the     dataset.
   <br>
   dataset: tbl_sqllite_customer<br>
   
   ![](query-step-8.png?raw=true)
   
updateby

1. Call the function "updateBy" and define the     dataset, by, operator and value.<br>
   ( We assumed you    have created the SQLiteTable in Services and    fill the info such as Name and fields. )
   <br>
   Dataset: tbl_sqllite_customer<br>
   by: code<br>
   operator: =<br>
   value: Code AAA<br>
   
   ![](query-step-9.png?raw=true)
   
   ![](query-step-10.png?raw=true)
   
2. Call the function "loadData" and define the     dataset.
   <br>
   dataset: tbl_sqllite_customer<br>
  
   ![](query-step-11.png?raw=true)
   
deleteBy

1. Call the function "deleteBy" and define the     dataset, by, and value.<br>
   ( We assumed you    have created the SQLiteTable in Services and    fill the info such as Name and fields. )
   <br>
   Dataset: tbl_sqllite_customer<br>
   by: code<br>
   value: Code BBB<br>

   ![](query-step-12.png?raw=true)
   
2. Call the function "loadData" and define the     dataset.
   <br>
   dataset: tbl_sqllite_customer<br>
 
   ![](query-step-13.png?raw=true)

