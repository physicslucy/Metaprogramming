
### 1
Write a function decorator, timethis, to calculate the time taken for the function to run

### 2
Define a function which returns the factorial of a number given as input (without using the built-in math.factorial function) and apply the @timethis decorator

###3 
Define a function which returns the factorial of a number given as input using the built-in math.factorial function and apply the @timethis decorator

###4 
Call the decorated functions to compare the efficiency of your method vs the math.factorial method for finding the factorial

###5
Print the metadata for your decorated functions : e.g. 
```python
func.__name__
```

###6
Remove the @wraps line from your decorator definition

Re-run the function definitons with decorators again

Reprnt the metadata for your decorated functions

###7
Undo the decorator function from the functions

###8
Compare the results from the decorator with the results from using the iPython magic %timeit, with your undecorated functions.

###9
Define the functions with both decorators: @record followed by @timethis

Note - this is a good example of how easy it is to add multiple decorators to the same function. 
This is useful because you can have very specific decorators and combine them to make the combination of operations you need for each function, without repeating the code for those operations for each function or defining different subclasses for the function to act on or within. 



Comment on the efficiency of the @record decorator by comparing the time taken with and without it
