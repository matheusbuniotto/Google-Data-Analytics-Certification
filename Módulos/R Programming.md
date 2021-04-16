### S2

#### Operadores
<- 
\- 
\+
/
\*

Logical operators return a logical data type such as TRUE or FALSE. 

3 tipos primários 

AND (sometimes represented as & or && in R)
OR (sometimes represented as | or || in R)
NOT (!)

if statement
The if statement sets a condition, and if the condition evaluates to TRUE, the R code associated with the if statement is executed.

In R, you place the code for the condition inside the parentheses of the if statement. The code that has to be executed if the condition is TRUE follows in curly braces (expr). Note that, in this case, the second curly brace is placed on its own line of code and identifies the end of the code that you want to execute. 

if (condition) {

 expr

}


#### Pacotes
Tidyverse: the tidyverse is a collection of R packages specifically designed for working with data. It’s a standard library for most data analysts, but you can also download the packages individually. 

Quick list of useful R packages: this is RStudio Support’s list of useful packages with installation instructions and functionality descriptions. 
https://support.rstudio.com/hc/en-us/articles/201057987-Quick-list-of-useful-R-packages


<b> Tidyverse </b>

#### Trabalhando com Pipes
%>% faz o output de um como input do otro
(and then)

função filter
função arrange
nested function - exemplo: arrange(filter(DataFrame, coluna == x), coluna )