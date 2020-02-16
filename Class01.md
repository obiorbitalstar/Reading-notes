# HTML , CSS , JS review  

html,css and javascript are three programing languges with 3 diffrent purposes but all depened on each other.
* Html:
html is the structure of the website (you can count it as the bones in a human body), its split to diffrent parts (head,body) the head is the part for the browser to read it  such as the web page title/language /version to deal with and a lot of diffrent things 
u can also do some linking in the head but that would be some spoliers for the upcoming parts of this article 
the other part of the html structure is the body , in the body is everything that will be shown to the user 
(headers articles images..etc) everything , thats why we tend to split the body into diffrent tags so we can navigate the code and the parts of the website easily 
every html code is inside somthing called "tag" ,there is two kind of tags , an opining tag which is at the start of the element and a closing one at the end 
it looks somthing like this 


"<tag>"some words "</tag>"


in html we have lots of features to interact with the user , one of this is forms 
specially in HTML5 where it has new and more form elements.
PS :Older browsers that do not understand HTML5
elements need to be told which elements are
block-level elements.(this was copied from the summary)



* CSS : 
css is a thing i can only descrpie by the words of a man which i forgot his name but he said 
> CSS to the website is like makup to the female 
it gives it life and color and makes everything more user friendly and lively , The css code is the same as the html in terms of syntax, In the end u add the css into the html file in one of three ways 
 * inline -> the css code is inside the html tag (the openinig tag)
 * internal -> in the html "head" u add a tag called "<style>" and inside this tag u put everything u want 
 * External -> U put all of the css in an outside file and link it inside the html file (the most professional way)
css gives a lot of control over images in particular, You can change the width and length and the way the images align 
you can also save data and space and time of loading of ur site has a lot of images to make things lighter for the user by using "Image sprites"  and u can also aplly animation effects on them but thats for future lessons 

* JavaScript : 
JavaScirpt is like the nerve system in the human body (makes everything interactive), without it the body is just a big lump of meat (and bones), so thats why js is very important (they all depened on each other as i have said before). you can use js in the html file almost like you use the css,internal (preferred at the end of the body so the user can see the html/css while the js codes and resources load) using the "<script></script>" tag, external by putting the js code in a diffrent file and linking it at the bottom of the body aswell (for the same reason).
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

scripts are basiclly are means to meet and end , you dont just randomly write a script you need to determined its purpose before writing it like you want a code to type a line 5 times there is many ways to do that like putting it in a consol.log 5 times or using a for loop, There is always a better soultion ,The more u learn the better you soultion will be.
in coding we using somthing called object , basiclly for a program anything the world can be counted as an object with data realted to it and constructors to handel that said data,evem web browsers are programs built using objects, Its how they see the web pages they recive the html code then read it and if the browser has a compiler/interpreter it will render the page if it had a css file and load it for the user. 


PS:Some early examples in this book do not work with Internet Explorer 8
and earlier (but alternative code samples that work in IE8 are available to
download from http:// j avascri pt book. com) (this was copied from the book exactly the same mostly for the link).

