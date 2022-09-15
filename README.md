# SQL_Study

### SELECT

SELECT column_name FROM table_name


### DISTINCT
SELECT DISTINCT column_name FROM table_name     
or     
SELECT DISTINCT (column_name) FROM table_name  

-> Combine the redundant components into one


### COUNT
SELECT COUNT column_name FROM table_name   
-> How many rows are there    
-> "SELECT COUNT * FROM table_name" shows the same result, because all column has the same number of rows.    


### COUNT + DISTINCT
Q. How many unique names are there in the table?     
-> SELECT COUNT (DISTINCT column_name) FROM table_name     
    or      
      SELECT COUNT (DISTINCT (column_name)) FROM table_name   
   

### WHERE
SELECT column1,column2 FROM table WHERE conditions;    

 * Comparison Operators
 =, >, <, >=, <=, <>/!=  
 
 * Logical Operators
 AND / OR / NOT  
 
 ex) SELECT name, choice FROM table WHERE name = 'David' AND choice = 'red'
 


