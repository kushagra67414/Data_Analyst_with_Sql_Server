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

