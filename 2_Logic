
#### Creating objects
 
R is an object-oriented programming language. That means that it allows you to store single values (think a number or text) as a “variable.” Basically, giving it a name. AKA variables in other programming languages. Use a carrat and dash to assign an object a value. Like this:
 
```{r}
<-  
```

 
*Create a new object, called “students” and assign the number of students in the room. Note: case (upper or lower) matters*
 

```{r}
> students <- 11
```
 
The object ‘students’ has now been stored. Notice that there was no output.
 
Use the print() command to see what’s stored in an object (or just type it’s name)

```{r}
>  print(students)
>  [1] 11
```
 

#### Data Types

There are different data types in programming languages. In R, the simplest are:

* Character: Comprised of text with quotations around it. Ex: “red”
* Numeric: Comprised of numbers
* Boolean: TRUE or FALSE
 
*Check the type of the object “students” with class()*
 
 
```{r}
> class(students)
```
 
The class should be numeric because we assigned a number to the object students
 
 
#### Vectors
A vector is basically a list of objects. For example:

 
```{r}
> list <- c(1,2,3)
```
        	
*Make a vector of prime numbers using the **concatenate notation** c(x,y,z)*
 
 ```{r}
> prime_numbers <- c(3,5,1)
> prime_numbers
> [1] 3 5 1
```	
 
You can put any kind of data into a vector.
 
*Overwrite students to make it a list of all our names. note: text goes in quotation marks)*
 
  ```{r}
> students <- c(name1, name2, name3)
```	
        	
 
Subsetting Vectors
You can “ask” your computer what value is in certain positions in the list. Example:
        	>  prime_numbers[3]
 	> [1] 1
 
*Subset the vector by using square brackets. Who is the second student in the list?
 
 	> students[2]
 
Conditional Subsetting
 
Conditional subsetting uses logical vectors. The below command will return any of the list that fit the criteria.
 
>  prime_numbers > 2
> [1] 1
 
 The only number in our list larger than 2 is 1.
 
 Conditional subsetting can also return TRUE or FALSE statements. For example:
	
> 3 > 4
> FALSE

Here’s where your “how to google lesson” comes in.
 
*Use your knowledge of conditional subsetting to figure out if our list of prime numbers is longer than 6. Hint: figure out what the command for how long a vector is! Talk to each other to figure it out. 
 
