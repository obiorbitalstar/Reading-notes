#  Images , Colors ,Text 

## Images
Images my be only a big gathring of pixles holding a diffrent values , But a single image can tell a whole story thats why selecting the right image for ur site is really imprtant and it can make or break the user experince
>A picture can say a thousand words 
To add an image to your project there is two ways but with the same tag 

* Via link: u get a link of an image online and put it in ur site :
```
<img src="some link of an online image"  alt ="if things go wrong show this " >
```

* from ur pc : you add an image to ur project and put the path to that said image via the img src tag aswell 
```
<img src="imgname.extention" alt="if things go wrong " >

```
the highet and width of an image and a lot of features about it can be controlled using CSS 

in html5 there is somthing called figur where u can show the image with a caption related to it 
a figure can also contain more than one image  and it looks like this :
```
<figure>
<img src="images/otters.jpg" alt="Photograph of
 two sea otters floating in water">
<br />
 <figcaption>Sea otters hold hands when they
 sleep so they don't drift away from each
 other.</figcaption>
</figure>
```
ps : code was taked direcly from the book for notes 

## Colors 
Choosing the right colors for your sight is very important and has great effects on the user experince, every website has a purpose and reason to be created , Some are for reading like blog some are for communication ,teaching  and so on 
so selcting the right color for ur site is crusal ,some colors are easy on the eyes while readin and some you use to poit out important notes and things that should be noticed imiditly... by now i think you get the gesture of what am talking about 
in css we have a lot of color features to choose from strating from the color of the text your writing to the color of the site and even the borders of each element  we have .

There are three ways to specify colors in CSS:
RGB values, hex codes, and color names.
CSS3 has introduced an extra value for RGB colors to
indicate opacity. It is known as RGBA.
X CSS3 also allows you to specify colors as HSL values,
with an optional opacity value. It is known as HSLA.
 (copied from the book)

 ## Text 
 Idk what to say about text its importance is pretty clear and html allows you to do so much to play around of how the texy is displayed ,font , size , font-family ..etc 
but there is things a person shuold consider before selecting a font family like the fact  that you dont know what would fonts the user would have installed on his device thats why we always have 3 font familes selected and its adviced to use the most common ones while selecting the font (Arial for example).

You can use pseudo-classes to change the style of an
element when a user hovers over or clicks on text, or
when they have visited a link (copied from the book)