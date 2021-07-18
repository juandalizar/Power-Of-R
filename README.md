![power of R1](https://user-images.githubusercontent.com/86560575/125981244-994ff9a8-4566-4a20-98f3-215968692276.JPG)

# Power-Of-R
Between covid 19 and taking advantage of time at home. I decide to join bootcamp data science at dibimbing.id in order to redeveloping my background statistics as well as switching career to data science possibility.

The beginning of bootcamp is starting introduce of power of R and this repository contain my summary knowledge from bootcamp data science.

## Everything in R is an object
it means an object is a data structure having some attributes/types and methods/function which act on its attributes. So Objects can be provided as input to functions. Since functions are objects, they, too, can be provided as input to other functions. [Object in R are assigned a value using <-, ->, and =, and the function are assigned a value using The _assign()_ Function](https://rpubs.com/aephidayatuloh/basicr01-assignment).

To know more *Everything in R is an object*, we should learn first Data types in R. [R has 5 often common used basic data types as below](https://www.datacamp.com/community/tutorials/r-objects-and-classes) :

1. Character, It can be alphabets or numbers, by quotes / double quotation marks ""
##### please see below example
```R-Studio markdown
foo <- "This is a character string!"  # we put character using "" then
foo  # we print the variable
```

2. Numeric (real or decimal), that have a decimal value or are a fraction in nature have a data type as numeric.
##### please see below example :
```R-Studio markdown
num <- 1.2   # we put 1.2 on the variable **num** then
print (num)   # we print the variable
```

3. Integer, indicates Numbers that do not contain decimal values have a data type as an integer or where the letter "L" declares this as an integer
##### please see below example :
```R-Studio markdown
y1 = 5L"  # we put integer using ‘L’ notation then
print(class(y1))  # we print the variable
```
R also supports integer data types which are the set of all integers. You can create as well as convert a value into an integer type using the as.integer() function.
##### please see below example :
```R-Studio markdown
x1 = 5                
print(class(x1))
[Output] "numeric"      # before using as.integer() function, R will read it as numeric

x = as.integer(x1)      # then we will use as.integer() to convert a value into an integer
print(class(x))
[Output] "integer"
```
Integer without the L will be saved as doubles/numeric as we can see the only difference between 5 and 5L.

4. Logical, indicates a variable that can have a value of TRUE and FALSE like a boolean is called a logical variable
##### please see below example :
```R-Studio markdown
lgl_var <- c(TRUE, FALSE)
print (lgl_var)   # we print the variable
``` 

6. Factor, They are a data type that is used to refer to a qualitative relationship like colors, good & bad, course or movie ratings, etc. They are useful in statistical modeling.
##### please see below example :
```R-Studio markdown
fac <- factor(c("good", "bad", "ugly","good", "bad", "ugly"))
print(fac)   # we print the variable

[Output] good bad  ugly good bad  ugly
Levels: bad good ugly
``` 
we also have the data type [date](https://rdrr.io/r/base/as.Date.html) and [complex](https://www.tutorialspoint.com/r/r_data_types.htm) as we focus on the main ones and this data type is rarely used in practice. for data type date, we can also klik ini this link : [1](https://www.stat.berkeley.edu/~s133/dates.html), [2](https://r4ds.had.co.nz/dates-and-times.html), [3](https://stats.idre.ucla.edu/r/faq/how-does-r-handle-date-values/), and [4](https://www.r-bloggers.com/2013/08/date-formats-in-r/).

#### Basic Operation in R (R Arimatic Operators)
thru the object or the funtion had been assigned, R allow us to do math operation using Arithmetic Operators like sums, divisions or multiplications, among others. [Here is a list of arithmetic operators available in R](https://r-coder.com/operators-r/)
![Arithmetic operators in R 2](https://user-images.githubusercontent.com/86560575/126054485-5cf983f9-cccc-4391-9762-feaab6ec4e8a.jpg)

```R-Studio markdown
#-----------------
# Basic operations
#-----------------

x <- 8
y = 3

# Addition operator (+), : The values of both the operands are added
print (x+y)   # 8

# Subtraction Operator (-) : The second operand values are subtracted from the first
print (x-y)   # 5

# Multiplication Operator (*) : The values of both the operands are multiplied with the use of ‘*’ operator
print (x*y)   # 24

# Division Operator (/) : The first operand is divided by the second operand with the use of ‘/’ operator
print (x/y)   # 2.67

# Exponential / Power Operator (^ or **) : The first operand is raised to the power of the second operand.
print (x^y)   # 512
print (x**y)   # 512

# Modulo Operator (%%) : The remainder of the first operand after divided by the second operand is returned.
print (x%%y)   # 2

# Floor division (%/%) or integer division : The result of division of x with y but rounded down (integer divide)
5 %/% 3 # 1
``` 
