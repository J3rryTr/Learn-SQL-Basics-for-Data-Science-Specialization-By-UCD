# SUMMARY COURSE
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

Specifies a range of condition comma delimited list of value, for example:

<div style="text-align:center">
<img src="https://github.com/J3rryTr/Learn-SQL-Basics-for-Data-Science-Specialization-By-UCD/blob/main/1.SQL%20fo%20Data%20Science/imgs/INOperator.png" alt="INOperator" width="480">
</div>    

#### OR operator

Use for any rows matching the specific conditions.

<div style="text-align:center">
<img src="https://github.com/J3rryTr/Learn-SQL-Basics-for-Data-Science-Specialization-By-UCD/blob/main/1.SQL%20fo%20Data%20Science/imgs/OROperator.png" alt="OROperator" width="640 height="480">
</div>    

### NOT operator

Use for show a condition

<div style="text-align:center">
<img src="https://github.com/J3rryTr/Learn-SQL-Basics-for-Data-Science-Specialization-By-UCD/blob/main/1.SQL%20fo%20Data%20Science/imgs/NOTOperator.png" alt="NOTOperator" >
</div>    


![Alt text](https://github.com/J3rryTr/Learn-SQL-Basics-for-Data-Science-Specialization-By-UCD/blob/main/1.SQL%20fo%20Data%20Science/imgs/SyntaxNOT.png)



### Wildcards
- Use % for wildcard
- Special character used to match parts of a value
- Search pattern made from literal on wildcard character of combination
- Use LIKE as an operator
- Only used with strings but cannot uses for non-datatype.


| Wildcard | Action |
| -------- | -------- |
| %object | Grabs anything ending with the word |  
| object% | Grabs anything before with the word |
| %object% | Grabs anything before and ending with the word |
| S%E | Grabs anything that start with "S" and end "E" the word |
| t%@gmail.com | Grab gmail addresses that start with "t" |

Underscore for wildcard
- Matches a single character
- It is not supported by DB2    
<strong> WHERE size LIKE '_pizza' --> spizza /mpizza </strong>(In a list of table) 


### Sorting with ODER BY
<strong> SELECT column FROM table   
ODER BY characteristic</strong>   
RULE:   
    - Take name of 1 or more columns        
    - Add a comma after each additional column name     
    - Can sort by a column not retrieved    
    - Must always be the last clause in a select statement  


- Sorting by column position    
<div style="text-align:center">
<img src="https://github.com/J3rryTr/Learn-SQL-Basics-for-Data-Science-Specialization-By-UCD/blob/main/1.SQL%20fo%20Data%20Science/imgs/SortingByColumn.png" alt="SortingByColumn" >
</div>    


- Sort direction    
<strong>DESC</strong>: descending order     
<strong>ASC</strong>: ascending order   
--> Only applying to the column names it directly precedes.     


### Aggregate functions
- Used to summarize data        
- Finding       
>the higher and lower values   
>the total number of row       
>the avg
- The Function:     
<strong>
>AVG()      
>COUNT()        
>MIN()      
>MAX()      
>SUM()      
</strong>     

The AVERAGE Function        
<div style="text-align:center">
<img src="https://github.com/J3rryTr/Learn-SQL-Basics-for-Data-Science-Specialization-By-UCD/blob/main/1.SQL%20fo%20Data%20Science/imgs/avgFunc.png" alt="avgFunc" >
</div>    


The COUNT Function      
<div style="text-align:center">
<img src="https://github.com/J3rryTr/Learn-SQL-Basics-for-Data-Science-Specialization-By-UCD/blob/main/1.SQL%20fo%20Data%20Science/imgs/CountFunc.png" alt="CountFunc" >
</div>    


The MAX and MIN Function        

NULL value are ignored by the MIN and MAX functions     

<div style="text-align:center">
<img src="https://github.com/J3rryTr/Learn-SQL-Basics-for-Data-Science-Specialization-By-UCD/blob/main/1.SQL%20fo%20Data%20Science/imgs/MaxFunc.png" alt="MaxMFunc" >
</div>    
<div style="text-align:center">
<img src="https://github.com/J3rryTr/Learn-SQL-Basics-for-Data-Science-Specialization-By-UCD/blob/main/1.SQL%20fo%20Data%20Science/imgs/MaxxFunc.png" alt="MaxxFunc" >
</div>      
The MIN same thing

The SUM Function        
<div style="text-align:center">
<img src="https://github.com/J3rryTr/Learn-SQL-Basics-for-Data-Science-Specialization-By-UCD/blob/main/1.SQL%20fo%20Data%20Science/imgs/SumFunc.png" alt="SumFunc" >
</div>    



Using DISTINCT:     
- If DISTINCT is not specified, ALL is assumed      
- Cannot use DISTINCT on COUNT(*)       
- No value use MIN and MAX function     
<div style="text-align:center">
<img src="https://github.com/J3rryTr/Learn-SQL-Basics-for-Data-Science-Specialization-By-UCD/blob/main/1.SQL%20fo%20Data%20Science/imgs/UsingDistinct.png" alt="UsingDistinct" >
</div>      


### Grouping Data
- Using <strong>GROUP BY</strong>