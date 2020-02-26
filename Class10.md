# Error Handling & Debugging 
when handling errors there is some things you need to take into considrations, And since there is new use in writing those things in diffrent matter than the book already provided am just gonna copy most of the thigns from the book into this page ( the things i find useful or new)

 ## Order of excution 
 it helps to know how scripts are processed.
The order in which statements are executed can be complex; some tasks
cannot complete until another statement or function has been run:
## EXECUTION CONTEXTS  
The JavaScript interpreter uses the concept of execution contexts.
There is one global execution context; plus, each function creates a new
new execution context. They correspond to variable scope. 

js interpertetr reads one line of code at a time, and when this code needs data from another palce it puts it on hold and stacks the other lines over it until the line with the data needed comes and both runs .

## scoop 
In the interpreter, each execution context has its own va ri ables object.
It holds the variables, functions, and parameters available within it.
Each execution context can also access its parent's v a ri ables object.

## errors 
If a JavaScript statement generates an error, then it throws an exception.
At that point, the interpreter stops and looks for exception-handl ing code. 
( try / catch should be readed about more )


## console 
console.log everrrrrrrythiiiiiiiiiiiiiiiiiiiiiing before calling the ta's