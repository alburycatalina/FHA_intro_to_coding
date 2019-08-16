## Coding Logic

### Creating objects
 
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
 

### Data Types

There are different data types in programming languages. In R, the simplest are:

* Character: Comprised of text with quotations around it. Ex: “red”
* Numeric: Comprised of numbers
* Boolean: TRUE or FALSE
 
*Check the type of the object “students” with class()*
 
 
```{r}
> class(students)
```
 
The class should be numeric because we assigned a number to the object students
 
 
### Vectors
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
        	
 
### Subsetting Vectors
You can “ask” your computer what value is in certain positions in the list. Example:

  ```{r}
>  prime_numbers[3]
> [1] 1
```	

 
#### *Subset the vector by using square brackets. Who is the second student in the list?*

 
### Conditional Subsetting
 
Conditional subsetting uses logical vectors. The below command will return any of the list that fit the criteria.

  ```{r}
>  prime_numbers > 2
> [1] 1
 ```
 The only number in our list larger than 2 is 1.
 
 Conditional subsetting can also return TRUE or FALSE statements. For example:
  ```{r}
> 3 > 4
> FALSE
 ```

Here’s where your “how to google lesson” comes in.
 
#### *Use your knowledge of conditional subsetting to figure out if our list of prime numbers is longer than 6. Hint: figure out what the command for how long a vector is! Talk to each other to figure it out.*


(5 minute break)



 
## Starting with Data
 
### Long form Data Structure
You might be used to using excel to create tables that look functional, but when you start to begin with code, you’ll want to use long form data structure, which means that each observation is a row. Use .csv files for code. You can open .csv files with excel, they’re pretty much the same but don’t save formatting. You can convert excel files to csv with the “save as” option in excel.

#### *Download the CSV from this repository into the folder you made earlier.*

Note long-form data structure (each observation is a row)! How exciting!


### Databasin’
This data was collected in a Bahamian shark survey. Each row is an observation of shark data, along with site, an ID, year, depth, visibility underwater, and count (how many sharks were seen).
 
### Importing Data

#### *Open Rstudio and set your working directory to the folder you made. Use the read.csv command to import the data. Save it as the object of your choice*

  ```{r}
> setwd(‘folder_name’)
> shark_data <- read.csv(‘shark_data.csv')
 ```

Sometimes databases are massive. Use head() to view the first few lines of data and get an idea of what it looks like.


#### *Use the head() command on the dataframe you just saved*

 
### Indexing
You can use indexing to select out values from your vector. Indexing uses the [row, column] notation.  For example:

  ```{r}
> shark_data[1,1] 
 ```

Will display the data in the first row and first column of the data frame. 


#### *Use indexing to figure out the common name of the 5th shark to be seen

You can also use commas to indicate selecting the whole row or column.  For example:
 
 ```{r}
> shark_data [,1]
 ```
Will display all of the observations in the first column! 


#### *Try it out! Use indexing to display only the 3rd shark observation (a row)*

You can also use the dollar sign to achieve a similar resulrts in data tables. The dollar sign works with column names in a table. Like this:

 ```{r}
> shark_data$site_name
 ```
 
Which returns all site names in the site_name column.


