# Data_Analyst_with_Sql_Server

##   Already started my course from DataCamp 

` Total 11 courses` 

>Will try to update my progess at alternate days.
 
 
## Course-1 Accomplisment
   
[Introduction to SQL Server](https://www.datacamp.com/statement-of-accomplishment/course/88e32108703000f83a0330cc2d9e6c45e013e608)
https://www.datacamp.com/statement-of-accomplishment/course/88e32108703000f83a0330cc2d9e6c45e013e608

## Course-2 Accomplisment

[Introduction to Relational Databases in SQL](https://www.datacamp.com/statement-of-accomplishment/course/dbf15c0aa657cd9671c5bad590f4db839d5bd6ef)

https://www.datacamp.com/statement-of-accomplishment/course/dbf15c0aa657cd9671c5bad590f4db839d5bd6ef


## Course-3

               `CHAPTER -1`
 * Summarizing Data
 * Commom Statistic
 * Where Clause
 * Subtotaling Aggregation with Groups
 * HAVING is WHERE for AggregatioN
 * FINDING AND RESOLVING MISSING DATA
 * SQL Statement using COALESCE
 * BINNING DATA WITH CASE
 
                `CHAPTER -2`
  
  * **COUNTS AND TOTALS**
  * **COUNT AGGREGATION**
  * **MATHS WITH DATES**
  * **DATEADD & DATEDIFF**
  * **ROUNDING AND TRUNCATING NUMBERS**
  * **MORE MAATHS FUNCTION**

                `CHAPTER -3`

  * **WHILE LOOP**
  * **DECLARED VARIABLE**
  * **DERIVED TABLES**
  * **CTE [COMMON TABLE EXPRESSION]**
  
  
                `CHAPTER -4`
                
  * **WINDOWS FUNCTION**
  * **FIRST_VALUE() & LAST_VALUE()**
  * **LEAD() AND LAG()**
  * **INCREASING WINDOWS COMPLEXITY**
  * **Using windows for calculating statistics**
  * **LIKE STDEV() AND MODE**
  
       ## Course-4 (TIME SERIES ANALYSIS IN SQL SERVER)

                  `**Chapter-1**`
                 
  * **Building dates**
  * **Comparing dates**
  * **Formatting dates for reporting**
  * **Working with calender tables**
  *  **CAST() , CONVERT() , AND FORMAT() FUNC**
  
                 `Chapter-2`
  today done with :
  * **Building dates from parts**
  * **Dates from part**
  * **Working with offsets**
  * **different between cast() and convert() and cost of parsing**
  * **Translating date strings**
  * **Casting strings**
  * **Converting Strings**
  * **Parsing strings**
  
  THE COST OF PARSING :
           ``` | function | Conversions Per Second |
            | -------- | ---------------------- |
            | CONVERT() | 251,997 |
            | CAST() |  240,347 |
            | parse() | 12,620 |```
            
  * **Setting languages**
  * **Working with offset**
      
      > Changing offsets.  SYNTAX => `SWITCHOFFSET() as Col_name`
      
      > Converting to DATETIMEOFFSET.  SYNTAX=>  `TODATETIMEOFFSET()`
  * **Discovering time zones**
  * **HANDLING INVALID DATES**
         
    ``` Using safe functions like
         Using safe functions like
         TRY_CAST()
         TRY_CONVERT()
         TRY_PARSE()```
         
               `Chapter-3`
  
  LEARN ABOUT =>      
  * Basic aggregation function
  * FILTERING Aggregates with CASE.
  * Statistical aggregate functions.
  * LIKE :  STDEVP() , VAR() , VARP() ETC ETC.
  * MEDIAN with special builtin function:
               
               ```
               SELECT TOP(1)
               PERCENTILE_CONT(0.5)
               WITHIN GROUP (ORDER BY l.SomeVal DESC)
               OVER () AS MedianIncidents
               FROM dbo.LargeTable l;
               ```
   * Cost of median high. why ?
   * Downsampling and upsampling data
   * Grouping by ROLLUP, CUBE, and GROUPING SETS
   * Hierarchical rollups with ROLLUP
   * Cartesian aggregation with CUBE
   * Define grouping sets with GROUPING SETS
   
   
 Date : 11-july-2020
 
                `Chapter-4`
 LEARN ABOUT =>
 
 * Using aggregation functions over windows.
 * Ranking func line  DENSE_RANK() , RANK() ...ETC
 * Aggregations with empty windows
 * Calculating running totals and moving averages.
 * Windows and filtersand CTEs.
 * Finding maximum levels of overlap.
 
MOTTO : Common (and uncommon) time series problems.

Done With Course 4 of data analyst with sql server.

 
Date : 14- july-2020 

## COURSE - 5
   ## Functions for Manipulating Data in SQL Server
   
       `CHAPTER -1`
LEARN ABOUT :

* Data type Storage
* precision of decimal.
* IMPLICIT & EXPLICIT CONVERSION.
* Precedence of data types.
[click here to learn more](https://github.com/kushagra67414/Data_Analyst_with_Sql_Server/blob/master/Functions%20for%20Manipulating%20Data%20in%20SQL%20Server/chapter1.pdf)

       `CHATER - 2`
LEARN ABOUT :

* Higher Precision vs lower Precision.
* Datefromparts(YEAR() , MONTH() , DAY() )
* Performing Arithmetic operations on dates
* SYNTAX : DATEDIFF(datepart, startdate, enddate)
* SYNTAX : DATEADD(datepart, number, date)
* Validating if an expression is a date.
        > Syntax : ISDATE(expression)
* Set dateformat explicitly
        > SET DATEFORMAT {format}
        
* also set language EXPLICITYLY
        > SET LANGUAGE {language}
        
 [CAN CLICK HERE FOR FULL SYNTAX , PDF PROVIDED](https://github.com/kushagra67414/Data_Analyst_with_Sql_Server/blob/master/Functions%20for%20Manipulating%20Data%20in%20SQL%20Server/chapter2.pdf)
 
 
       
        `CHAPTER - 3`

LEARN ABOUT :

* Functions for Position.
           Functions like : LEN() , PATINDEX() , CHARINDEX()
* Function FOR STRING TRANSFORMATION.
           Function Like :  LOWER() & UPPER() , LTRIM() & RTRIM() & TRIM() , SUBSTRING() , REPLACE()
* Functions for Manipulating Groups Of Strings.
           Function like : CONCAT() & CONCAT_WS() , STRING_AGG() , STRING_SPLIT()


[Detail Learning for all the built-in Methods, CLICK HERE](https://github.com/kushagra67414/Data_Analyst_with_Sql_Server/blob/master/Functions%20for%20Manipulating%20Data%20in%20SQL%20Server/chapter3.pdf)

          `CHAPTER-4`
          
LEARN ABOUT :

* Aggregate arithmetic functions
* Analytic functions
like : FIRST_VALUE() / LAST_VALUE() 
SYNTAX : LAST_VALUE(numeric_expression)
OVER ([PARTITION BY column] ORDER BY column ROW_or_RANGE frame)  
* Partition limits
RANGE BETWEEN start_boundary AND end_boundary
ROWS BETWEEN start_boundary AND end_boundary
* Mathematical functions
LIKE : ABS(numeric_expression) / SIGN(numeric_expression) / 
* Rounding functions
1. CEILING(numeric_expression)
2. FLOOR(numeric_expression)
3. ROUND(numeric_expression, length)

* Exponential functions
1. POWER(numeric_expression, power)
2. SQUARE(numeric_expression)
3.  SQRT(numeric_expression)

[STATEMENT OF ACCOMPLISHMENT](https://www.datacamp.com/statement-of-accomplishment/course/733c7e90244ca2b1ca7ab5cf7a0a7e397176aa08)

`COMPLETE CHAPTER 5`
           
           
## COURSE -6  [ DATABASE DESIGN ]

         `CHAPTER-1`
   
 * OLAP AND OLTP
 * olap VS OLTP
 * Woking together OLAP (DATA Warehouse) OLTP(Operational Database)
 * Storing data ( Structured / Unstructured / Semi-Structured )
 * DATA LAKES (For Analyzing BIG datas)
 * Data Modeling
 * Dimensional Modelling
 [click here for details](https://github.com/kushagra67414/Data_Analyst_with_Sql_Server)
 
          `CHAPTER-2`
          
 * Star and snowflake schema
 * Normalisation and DeNormalisation Databases
 * OLTP Highly Normalized
 * Normal Forms 
 * Data Anomalies
 
          `CHAPTER-3  [Database View]`
          
 * Database views
 * Creating views
 * Benefits of views
 * Managing views
 * Granting and revoking access to a view
 * Updating a view
 * Inserting into a view
 * Dropping a view
 RESTRICT AND CASCADE
 * Redefining a view
 * Altering a view
 * Materialized View
 * Two types of views
 * When to use materialized views
 * Tools for managing dependencies
         
         `CHAPTER-4  [Database roles and access control ]`
         
 * Granting and revoking access to a view
 * Database roles
 * Create a role
 * GRANT and REVOKE privileges from roles
 * DATABASE DESIGN
 * Users and groups (are both roles)
 * Table partitioning
 * Vertical and Horizontal partitioning
 * Relation to sharding
 * Picking a Database Management System
 * Data integration
 
 [STATEMENT OF ACCOMPLISHMENT](https://www.datacamp.com/statement-of-accomplishment/course/160e9b5bdaab1a7e3214416f1f1bdd5d20c4ae79)
 
 
 
##   COURSE-7 [Hierarchical and Recursive Queries in SQL Server]

       `CHATER-1`
     
 * Recap of Common Table Expressions (CTE)
 * RECURSION 
 * RECURSION BY CTE (COMMON TABLE Expressions)
 
 [click here for more](https://github.com/kushagra67414/Data_Analyst_with_Sql_Server/blob/master/Hierarchical%20and%20Recursive%20Queries%20in%20SQL%20Server/chapter1.pdf)
 
       `CHAPTER-2`
   
 * Its was all about heirarchy
 * ANALYSING THE FAMILY TREE  
   
       `CHAPTER-3`
 
 * How to work with tables
 * Working with hierarchical data models
 * Working with Networks data models
 
        `CHAPTER-4`
        
 * Travel planning for FLIGHT DATA
 * How To assemble the Car.
 * Modeling a power Grid
 
 [STATEMENT OF ACCOMPLISHMENT](https://www.datacamp.com/statement-of-accomplishment/course/e7e794a3181693f26c6e525876b2f1a637155727)
 
 
##     COURSE-8 [Transactions and Error Handling in SQL Server]

       `CHAPTER-1 [ ERROR HANDLING ] `
* THE TRY...CATCH
* Nesting TRY...CATCH
* Error anatomy and uncatchable errors
* Giving information about errors
* Error functions

[Click here for details](https://github.com/kushagra67414/Data_Analyst_with_Sql_Server/blob/master/Transactions%20and%20Error%20Handling%20in%20SQL%20Server/chapter1.pdf)


       `CHAPTER-2 [ RAISERROR ] `
* RAISERROR with message string
* RAISERROR - Example with TRY...CATCH
* THROW
* Customizing error messages in the THROW
* The FORMATMESSAGE function.

[Click here for more details](https://github.com/kushagra67414/Data_Analyst_with_Sql_Server/blob/master/Transactions%20and%20Error%20Handling%20in%20SQL%20Server/chapter2.pdf)

       `CHAPTER-3 [ Transactions ] `
WITH A CASE STUDY 
*  Transaction statements - 1. BEGIN a transaction. 2. COMMIT a transaction. 3. ROLLBACK a transaction.
* what is @@TRANCOUNT ?
* Nested transactions
* Savepoints and its purpose
* XACT_ABORT & XACT_STATE [Most Imp].

[Click here for Details](https://github.com/kushagra67414/Data_Analyst_with_Sql_Server/blob/master/Transactions%20and%20Error%20Handling%20in%20SQL%20Server/chapter3.pdf)

       `CHAPTER-4 [ Transactions ] `
       
* Transaction isolation levels {MUST READ }
* Dirty reads
* Non-repeatable reads
* Phantom reads
* READ COMMITTED & REPEATABLE READ
* SNAPSHOT
* WITH (NOLOCK)

[Click here for Details](https://github.com/kushagra67414/Data_Analyst_with_Sql_Server/blob/master/Transactions%20and%20Error%20Handling%20in%20SQL%20Server/chapter4.pdf)


[STATEMENT OF ACCOMPLISHMENT](https://www.datacamp.com/statement-of-accomplishment/course/84007889facef60e22959255cd3a56f79834f331)


##          COURSE-9 [Writing Functions and Stored Procedures in SQL Server]


       `CHAPTER-1`
       
 * Variables for datetime data
 * Date manipulation.
 [click here for more](https://github.com/kushagra67414/Data_Analyst_with_Sql_Server/blob/master/Writing%20Functions%20and%20Stored%20Procedures%20in%20SQL%20Server/chapter1.pdf)
 
        `CHAPTER-2`
        
 * Scalar user defined functions
 * Modular programming
 * Table valued UDFs
 * Differences - ITVF vs. MSTVF
 * Maintaining user defined functions
 * Schemabinding
 
 [click here for more](https://github.com/kushagra67414/Data_Analyst_with_Sql_Server/blob/master/Writing%20Functions%20and%20Stored%20Procedures%20in%20SQL%20Server/chapter2.pdf)
 
 
       `CHAPTER-3`
       
  * Stored procedures
  * UDFs VS SPs
  * CRUD!
  * Let's EXEC!
  * THROW vs RAISERROR
  
  [click here for more](https://github.com/kushagra67414/Data_Analyst_with_Sql_Server/blob/master/Writing%20Functions%20and%20Stored%20Procedures%20in%20SQL%20Server/chapter3.pdf)

       `CHAPTER-4`
       
  * Case study EDA & imputation
  * Data and mean and hot deck imputation.
  * SHIFTS !!!
  * TEST SHIFTS IN SPs
  
  [click here for more](https://github.com/kushagra67414/Data_Analyst_with_Sql_Server/blob/master/Writing%20Functions%20and%20Stored%20Procedures%20in%20SQL%20Server/chapter4.pdf)
  
 
 [STATEMENT OF ACCOMPLISHMENT](https://www.datacamp.com/statement-of-accomplishment/course/0b7f5c5c05577a3c85fb181a758fa36ee55b38d7)
 
 
 
 ##         COURSE-10 [Building and Optimizing Triggers in SQL Server]
 
          `CHAPTER-1`
 * Types of Triggers
 a> based on T-SQL commands)
 b> based on behavior
 * How DML triggers re used
 * AFTER VS Instead of
 * Trigger alternatives
 
 [click here for more](https://github.com/kushagra67414/Data_Analyst_with_Sql_Server/blob/master/Building%20and%20Optimizing%20Triggers%20in%20SQL%20Server/chapter1.pdf)
 
          `CHAPTER-2`

 * More usage of tirggers
 * Logon triggers
 * why  AFTER ? Why FOR ?
 
 [click here for more](https://github.com/kushagra67414/Data_Analyst_with_Sql_Server/blob/master/Building%20and%20Optimizing%20Triggers%20in%20SQL%20Server/chapter2.pdf)

          `CHAPTER-3`

 * Known limitations of triggers
 * Finding triggers 
 * Methods to VIEW triggers.
 * Use cases for AFTER triggers (DML)
 * NOTIFY USERS
 * Use cases for INSTEAD OF triggers (DML)
 * Use cases for *~DDL~* triggers
 
 [click here for more](https://github.com/kushagra67414/Data_Analyst_with_Sql_Server/blob/master/Building%20and%20Optimizing%20Triggers%20in%20SQL%20Server/chapter3.pdf)
 
 
           `CHAPTER-4`
 * Deleting and altering triggers
 LIKE => ALTERING / DISABLING/ ETC ETC
 * Trigger management
 * Getting info from sys.triggers
 * Troubleshooting triggers
 
 [click here for more](https://github.com/kushagra67414/Data_Analyst_with_Sql_Server/blob/master/Building%20and%20Optimizing%20Triggers%20in%20SQL%20Server/chapter4.pdf)
 
 [STATEMENT OF ACCOMPLISHMENT](https://www.datacamp.com/statement-of-accomplishment/course/611d2c99bb89ecdfcbdd4b5a73f8005d8e7a930d)
 
 
 
 ##           COURSE-11 [Improving Query Performance in SQL Server]
 
 
      `CHAPTER-1`
      
* Commenting blocks AND lines.
* Aliasing
* Renamed columns
* Query order
* Syntax order
* Logical processing order

[Click here for more Details](https://github.com/kushagra67414/Data_Analyst_with_Sql_Server/blob/master/Improving%20Query%20Performance%20in%20SQL%20Server/chapter1.pdf)

      `CHAPTER-2`
* Filtering with WHERE
* WHERE processing order
* using sub - query
* Functions on columns OR where
* Filtering with HAVING
* Interrogation after SELECT
* Managing duplicates
* Distint() / union()

[Click here for more Details](https://github.com/kushagra67414/Data_Analyst_with_Sql_Server/blob/master/Improving%20Query%20Performance%20in%20SQL%20Server/chapter2.pdf)

      `CHAPTER-3`

* Sub-queries
* Presence and absence
* INTERSECT and EXPECT
* JOINS

[Click here for more Details](https://github.com/kushagra67414/Data_Analyst_with_Sql_Server/blob/master/Improving%20Query%20Performance%20in%20SQL%20Server/chapter3.pdf)

      `CHAPTER-4`
      
* Time statistics
* Page read statistics
* What are INDEXs
* Execution plans
* Query performance tuning
[Click here for more Details](https://github.com/kushagra67414/Data_Analyst_with_Sql_Server/blob/master/Improving%20Query%20Performance%20in%20SQL%20Server/chapter4.pdf)

[STATEMENT OF ACCOMPLISHMENT](https://www.datacamp.com/statement-of-accomplishment/course/aac1ba08ddc708b121eeb477b92da8bbb58fad77)


# COMPLETE THE COURSE : THE DATA ANALYST WITH SQL SERVER


[STATEMENT OF ACCOMPLISHMENT OF COMPLETE COURSE](https://www.datacamp.com/statement-of-accomplishment/track/ec323863f83cfd32a6e9446d95cf780cda6104b6)

Thank You !!!!!
