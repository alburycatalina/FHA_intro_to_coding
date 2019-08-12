# A bit of background

Open up Rstudio and we'll go through the various aspects of the IDE. 

**Running/ executing a command**: Tells the computer to follow the instructions

### The Console
**Console**: Where commands are automatically executed by the computer. In the console, you'll notice the "more than" sign or "carat". This means R is good to go and accept a command. A plus sign means that the command is incomplete and you need to say more. Press esc if you want to cancel what you typed to get back to the >.



For example:

```{r}
  > 2 + 2
 	> [1] 4
```


 
Note the 1 in brackets. That means that the output is a single value
 
 ```{r}
 	> 2 +
 	+
```

 
*Write a complete command with addition, subtraction, or multiplication. Write an incomplete command and finish it on the second line
 
 
**Script editor**: Allows for your code to be reproducible. Save the code to run later. You can run code directly from the script editor in Rstudio too. Save files here the same way you do a word document. Rstudio is a script editor or IDE, also known as “interactive development environment.” You can type r code directly into the terminal on your computer, but Rstudio helps you to do it in an easy way. A little like wordpad vs. microsoft word. 

**Working Directory*: The place on your machine where the files you create are saved and the files you read from can be found (more on this later)


### Annotation
You will want to make comments on your code. Use the hashtag before writing these. This will run:
 
> 2 + 2
> [1] 4
 
This will not produce an output.
 
> # 2 + 2
 
From now on, make comments on your code explaining what it does. You will thank yourself later when going back to the lesson.  
 
Example:
 	> # R can be used as a calculator
 	> 2 + 2
> [1] 4
 	> # The output is four
