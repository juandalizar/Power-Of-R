![power of R1](https://user-images.githubusercontent.com/86560575/125981244-994ff9a8-4566-4a20-98f3-215968692276.JPG)

# Power-Of-R
Between covid 19 and taking advantage of time at home. I decide to join bootcamp data science at dibimbing.id in order to redeveloping my background statistics as well as switching career to data science possibility.

The beginning of bootcamp is starting introduce of power of R and this repository contain my summary knowledge from bootcamp data science.

## Everything in R is an object.

### R has 4 often common used basic data types as below

1. character
It can be alphabets or numbers, by quotes / double quotation marks ""
`foo <- "This is a character string!"  # we put character using "" ` then
`foo  # we print the variable`

2. numeric (real or decimal) 
Numbers that have a decimal value or are a fraction in nature have a data type as numeric. for Example :
`num <- 1.2   # we put 1.2 on the variable **num**` then
`print (num)   # we print the variable`

3. integer
indicates Numbers that do not contain decimal values have a data type as an integer or where the letter "L" declares this as an integer
`y1 = 5L"  # we put integer using ‘L’ notation` then
`print(class(y1))  # we print the variable`

R supports integer data types which are the set of all integers. You can create as well as convert a value into an integer type using the as.integer() function
`x1 = 5`
`print(class(x1))`
`x = as.integer(x1)`
`print(class(x))`

4. logical
A variable that can have a value of TRUE and FALSE like a boolean is called a logical variable 
`lgl_var <- c(TRUE, FALSE)`
