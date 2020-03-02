# Canvas handling 
## The canvas element 
element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high.
example of creating a canvas tag :
```
<canvas id="stockGraph" width="150" height="150">
  current stock price: $3.15 + 0.15
</canvas>

```

## Drawing text
The canvas rendering context provides two methods to render text:

``` fillText(text, x, y [, maxWidth]) ``` 
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
```strokeText(text, x, y [, maxWidth])```
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw. 

 ## Applying styles and colors

### Colors
color is a string representing a CSS ```<color>```,
 a gradient object, or a pattern object. We'll look at gradient and pattern objects later. By default, the stroke and fill color are set to black (CSS color value #000000). 
 there are many ways to apply colors to the canvas text using the hexadecimal value or typeing the color name it self and so on. 
 examples :
 ```
 // these all set the fillStyle to 'orange'
ctx.fillStyle = 'orange';
ctx.fillStyle = '#FFA500';
ctx.fillStyle = 'rgb(255, 165, 0)';
ctx.fillStyle = 'rgba(255, 165, 0, 1)';

 ```
## Drawing shapes with canvas
after u set up a canvas enviroment,you can get into the details of how to draw on the canvas  

### Drawing rectangles
 There are three functions that draw rectangles on the canvas:
 * ```fillRect(x, y, width, height) ``` 
  Draws a filled rectangle.

* ``` strokeRect(x, y, width, height) ``` 
Draws a rectangle outline 

* ``` clearRect(x, y, width, height) ``` 
Clears the specified rectangular area, making it fully transparent. 

example : 
```
function draw() {
  var canvas = document.getElementById('canvas');
  if (canvas.getContext) {
    var ctx = canvas.getContext('2d');

    ctx.fillRect(25, 25, 100, 100);
    ctx.clearRect(45, 45, 60, 60);
    ctx.strokeRect(50, 50, 50, 50);
  }
}

```

