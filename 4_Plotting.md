## Plotting

Let’s show off this data with some Base R plotting! plot(x,y) is one of the simplest plot functions to use. It accepts x and y arguments in order. 

#### *Plot the data in the data frame you just made with count per site. Hint: use the dollar sign indexing that we learned earlier (ex: data$column).*

Now that you’ve made your plot, let’s get a little fancier. Add axis labels to your plots by including xlab and ylab arguments. 

```{r}
> plot(x, y, 
	xlab= “”, 
	ylab = “”). 
```
	

Example: 

```{r}
> plot(new_data3$site_name, new_data3$count, 
	xlab= "x label", 
	ylab = "y label")
```

#### *Add some axis labels that make sense to the plot. 

Let’s save your plot as a pdf for later. Use the save button above the plot to do so. 

(5 min break)
