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
           
           
## COURSE -6

         `CHAPTER-1`
   
 * OLAP AND OLTP
 * olap VS OLTP
 * Woking together OLAP (DATA Warehouse) OLTP(Operational Database)
 * Storing data ( Structured / Unstructured / Semi-Structured )
 * DATA LAKES (For Analyzing BIG datas)
 * Data Modeling
 * Dimensional Modelling
 [click here for details](https://github.com/kushagra67414/Data_Analyst_with_Sql_Server)
 
