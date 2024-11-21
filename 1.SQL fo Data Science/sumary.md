# Course 1: Learn SQL basic syntax
## Certificate
![Alt text](https://github.com/J3rryTr/Learn-SQL-Basics-for-Data-Science-Specialization-By-UCD/blob/main/1.SQL%20fo%20Data%20Science/C1.png)

## Relation database models, define and describe both relational and transactional database models

| Relation | Transaction |
|-------|------|  
| Show the relationships between different tables and optimize data, making it easy and intuitive to access the data.| Operational database insurance claims within a healthcare database |   

### Relationship
- ER diagram   
    - Show a relationship
    - Business process
    - Represented visually  


| Primary | Foreign |
|---------|----------|
| A column whose value uniquely identify every row in the table | One of more column that can be used together to identify a single row in another table |


ER diagram        

Chen Notation   
<div style="text-align:center">
<img src="https://github.com/J3rryTr/Learn-SQL-Basics-for-Data-Science-Specialization-By-UCD/blob/main/1.SQL%20fo%20Data%20Science/imgs/ChenNotation.png" alt="ChenNotation" width="640" height="480">
</div>      

Crow's foot notation    
<div style="text-align:center">
<img src="https://github.com/J3rryTr/Learn-SQL-Basics-for-Data-Science-Specialization-By-UCD/blob/main/1.SQL%20fo%20Data%20Science/imgs/Crow'sNotation.png" alt="Crow's Foot Notation" width="640" height="480">
</div>      
  
UML class   
<div style="text-align:center">
<img src="https://github.com/J3rryTr/Learn-SQL-Basics-for-Data-Science-Specialization-By-UCD/blob/main/1.SQL%20fo%20Data%20Science/imgs/UMLClass.png" alt="UML Class" width="640" height="480">
</div>   


SQL Syntax
SELECT: selection column    
FROM: specific table    
LIMIT: limited show the number of rows  
NULL: whether column can accept value or not    

Create and adding value into a table

- For example   
<div style="text-align:center">
<img src="https://github.com/J3rryTr/Learn-SQL-Basics-for-Data-Science-Specialization-By-UCD/blob/main/1.SQL%20fo%20Data%20Science/imgs/eg1.png" alt="eg1" width="640" height="480">
</div>      

<div style="text-align:center">
<img src="https://github.com/J3rryTr/Learn-SQL-Basics-for-Data-Science-Specialization-By-UCD/blob/main/1.SQL%20fo%20Data%20Science/imgs/eg2.png" alt="eg2" >
</div>      

Create Temporary tables     
The temporary table can be deleted when current session is terminated   
How to create Temporary table   
<div style="text-align:center">
<img src="https://github.com/J3rryTr/Learn-SQL-Basics-for-Data-Science-Specialization-By-UCD/blob/main/1.SQL%20fo%20Data%20Science/imgs/CreateTemporaryTable.png" alt="TB1">
</div>      


## Filtering 
Use the WHERE claude operator looking for column name operator value.
<div style="text-align:center">
<img src="https://github.com/J3rryTr/Learn-SQL-Basics-for-Data-Science-Specialization-By-UCD/blob/main/1.SQL%20fo%20Data%20Science/imgs/FilteringUseWHERE.png" alt="FilteringUseWHERE">
</div>   

<div style="text-align:center">
<img src="https://github.com/J3rryTr/Learn-SQL-Basics-for-Data-Science-Specialization-By-UCD/blob/main/1.SQL%20fo%20Data%20Science/imgs/WHEREClauseOperators.png" alt="WHEREClauseOperators" width="640" height="480">
</div>   


For example:        
<div style="text-align:center">
<img src="https://github.com/J3rryTr/Learn-SQL-Basics-for-Data-Science-Specialization-By-UCD/blob/main/1.SQL%20fo%20Data%20Science/imgs/eg3.png" alt="eg3" width="640" height="480">
</div>   


<div style="text-align:center">
<img src="https://github.com/J3rryTr/Learn-SQL-Basics-for-Data-Science-Specialization-By-UCD/blob/main/1.SQL%20fo%20Data%20Science/imgs/eg4.png" alt="eg4" height="480">
</div>    


The Checking for Non-Matches    
<div style="text-align:center">
<img src="https://github.com/J3rryTr/Learn-SQL-Basics-for-Data-Science-Specialization-By-UCD/blob/main/1.SQL%20fo%20Data%20Science/imgs/Checking4NonMatches.png" alt="Checking4NonMatches" width="640" height="480">
</div>    

Filter with a range value
<div style="text-align:center">
<img src="https://github.com/J3rryTr/Learn-SQL-Basics-for-Data-Science-Specialization-By-UCD/blob/main/1.SQL%20fo%20Data%20Science/imgs/FilteringWithARange.png" alt="FilteringWithARange" width="640"  height="480">
</div>    


Filter No Value
<div style="text-align:center">
<img src="https://github.com/J3rryTr/Learn-SQL-Basics-for-Data-Science-Specialization-By-UCD/blob/main/1.SQL%20fo%20Data%20Science/imgs/Filter0Value.png" alt="Filter0Value">
</div>    


### Advance filtering
#### IN operator

<div style="text-align:center">
<img src="https://github.com/J3rryTr/Learn-SQL-Basics-for-Data-Science-Specialization-By-UCD/blob/main/1.SQL%20fo%20Data%20Science/imgs/INOperator.png" alt="INOperator" width="480">
</div>    

#### OR operator

<div style="text-align:center">
<img src="https://github.com/J3rryTr/Learn-SQL-Basics-for-Data-Science-Specialization-By-UCD/blob/main/1.SQL%20fo%20Data%20Science/imgs/OROperator.png" alt="OROperator" width="640 height="480">
</div>    

### NOT operator

<div style="text-align:center">
<img src="https://github.com/J3rryTr/Learn-SQL-Basics-for-Data-Science-Specialization-By-UCD/blob/main/1.SQL%20fo%20Data%20Science/imgs/NOTOperator.png" alt="NOTOperator" >
</div>    


![Alt text](https://github.com/J3rryTr/Learn-SQL-Basics-for-Data-Science-Specialization-By-UCD/blob/main/1.SQL%20fo%20Data%20Science/imgs/SyntaxNOT.png)