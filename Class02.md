# more info on HTML,CSS,Javascript 

## HTML : 
So basically html pages are text documents that are constructed from putting elements togather in some order to create a bigger picture , Those elements are usually called tags, The tags contain three parts (starting tag ,element content,ending tag) and you can give attributes to those tags ( you but them in the opening tag) u gave them value and name and lots of things.
### the more tags you know and understand the more you can do in html 
like editing on the text you display using tags like heading (from H1 to H6,h1 being the biggest) and using H1 is very important for your website for the SEO, also there is the paragraph tag "<p>" the name explains it self tbh, tags for bold and italic  "<b>" and "<i>" and so much more , as i said the more tags u know in html the more you can do and there is always somthing to learn. 
one of the good things to learn is to add an audio file to your html using the "<Audio>"  where you put it like this
```
<audio src="audio/test-audio.ogg"
 controls autoplay> 
 // this code was copied from the book for learning reasons
```

Audio is one of  self closing tags (meaning it dosnt have a closing tag it closes it self), To add audio /video or even animation you need  flash added to the browser (it dosent work on IOS systems "Iphone/Ipad"), also not all the browsers that support HTML5 support the same audio/video formats thats why we use diffrent formats for the same file so it runs for all the users who use diffrent browsers without any trouble.

## CSS:
css controls the way all the elements of the html are displayed for the user, it can be linked inside the said html page in diffrent ways 
 * inline -> the css code is inside the html tag (the openinig tag)
 * internal -> in the html "head" u add a tag called "<style></style>" and inside this tag u put everything u want 
 * External -> U put all of the css in an outside file and link it inside the html file (the most professional way)
the css is splited into a selctore and declaration , The selector is how you choose the html tag (or group of tags) that you want to apply mass changes on instead of doing the change over and over again for each tag alone (inline),the delcation is the set of changes that you want to do on that said tag , it gose somthing like this : 

```
p {
 font-family: Arial;} 
 //link copied from the book for study.

```
after the selector you put the declation inside curly braces and each every declaration line with ";". 

## Javascript 
you can use js in the html file almost like you use the css,internal (preferred at the end of the body so the user can see the html/css while the js codes and resources load) using the "<script></script>" tag, external by putting the js code in a diffrent file and linking it at the bottom of the body aswell (for the same reason) because the browsers runs the javascript where ever it finds it in the html page we put it at the end of the body.

java script is dynamic programming langue that follows most of the rules that all the other langues follow when it comes to declaring variables 

```
var x= 5; 
```

key word / variable name / the value after the "=" sign . 
one of the difrencess in javascrip is that while other langues requier the a datatype as the inital key word (double,int,string) javascript just asks to have the word "var" at the start of declaring a variable and depening on the value it deals with the vriable 

```
var x = 5; //this is a number (dosnt matter if its intger or double they are both in this catagory)
var y= "Hello" //this is a string 
var z= 'A' //this is a character 
``` 
 sometimes you just end up with too many variables to store so you use an array, in array is a vraiable that stores bunch of elements in one place instead of creating a diffrent variable for each element 
 to declar an array you use the var keyword then the var name then the elements put between brackets seperated by commas

 ```
 var x = [element1,element2,element3...,elementX]; 

 ```
 you can navigate through this array using "x.[elemntNumber1]" this basiclly mean "from the array named x bring me the element numebr 1" in the array the counting starts from 0 so element number 1 would be the 2nd element in the array.

 we talked about objects in general in the class-01 and now were gonna talk about a specific one called the date object 
 you declar the date object like you declar a normal variable 

 ```
var x  = new Date();

 ```
when u declar it this way x will store the date (year,month,day,hours,minutes,seconds) at the moment the interpreter reads the code 
you can spicify a date by filling the parameter with that date like 

```
var x= new Date('Apr 16, 1996 15:45:55 '); 

``` 
you can also use functions from this object to get the year/month/day and store them in seperate variables

```
var x  = new Date();
var year= x.getFullYear(); //we get the year stored in x 
var month = x.getMonth(); //we get the month stored in x
var day =x.getDay() ; // we get the day stored in x 
```
there is also functions to get hours,minutes and seconds but you get the point.

functions is a group of statments (code) put togather for us to use over and over again instead of writing the code mutiple time all over the project and wasting space /compiling time. 


