## Domain modeling
Domain modeling is the process of creating a conceptual model for a specific problem, Building the domain model well and in a good understandable way shows how much you understand the problem and how well you can handle it. 
you'll want to build self-contained objects with the same attributes and behaviors. That way, when you need to change the algorithm for your data and its input, the changes will be small and targeted.
to start a domain you do somthing like this : 
```
// declaring it
var EpicFailVideo = function(epicRating, hasAnimals) {
  this.epicRating = epicRating;
  this.hasAnimals = hasAnimals;
}
// passing values to control and using it 

var parkourFail = new EpicFailVideo(7, false);
var corgiFail = new EpicFailVideo(4, true);

```

(stuff coopied from the atricle)
* Model its attributes with a constructor function that defines and initializes properties.
* Model its behaviors with small methods that focus on doing one job well.
* Create instances using the new keyword followed by a call to a constructor function.
* Store the newly created object in a variable so you can access its properties and methods from outside.
* Use the this variable within methods so you can access the object's properties and methods from inside.

## Tables
Tables are a set of columns and rows that you can put elements inside of them, They are usfule when it comes to deviding the page or seperating / showing data in an ordered and organized way (they are shows as a grid view)
the "tr " tag is using to start a row and the "td" for colmuns, You can divide the table into head body and foot aswell 
"thead", "tbody" , "tfoot" to mange and map it better 

##  Objects 
we already defined and talked about objects before, Now we will deal with a new kind of objects 
the constructor notation object 
to declar it you just type 
```
var name = new Object();
// with this we created an object using the key word "new " and can access this object /add to it using the variable name

```
Objects are flixable, They can be made as arrays or simple put multiple objects in an array, They can be gloable or inside a small scoop, they can have parameters or go without any, Simply play around with them to know thier full extent and ablility. 
variables inside an object are called properties and functions inside an object gets called methods. 
kinda diffrent in the way you decalre them but still with the same use.

