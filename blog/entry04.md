# Entry 4
##### 3/14/26
The tool that I chose for the freedom project was A-Frame. The way to start tinkering with this tool was by going to the website aframe.io and using their starter code. This is what the starter code looked like:
```html
<html> <head> <script src="https://aframe.io"></script> </head> <body> <a-scene> <a-box position="-1 0.5 "-3"" rotation="0 45 0" color="#4CC3D9"></a-box> <a-sphere position="0 1.25 "-5"" radius="1.25" color="#EF2D5E"></a-sphere> <a-cylinder position="1 0.75 "-3"" radius="0.5" height="1.5" color="#FFC65D"></a-cylinder> <a-plane position="0 0 "-4"" rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane> <a-sky color="#ECECEC"></a-sky> </a-scene> </body> </html> 
```

What this did is it made different shapes of different sizes, and you can go around and look at them from different angles. After looking at this code, I saw how each line of code was able to make a different shape. Along with that, I also saw how their color was decided through:
```html
color=”” 
Use the code with caution.
And I also saw how things that decided the shapes' dimensions were made. With this information, I changed a few things. I changed the cylinder height from 1.5 to 3. Then I changed the radius of the cylinder from .5 to 2. So this is what the code looked like now:
```html
<a-scene> <a-box position="-1 0.5 "-3"" rotation="0 45 0" color="#4CC3D9"></a-box> <a-sphere position="0 1.25 "-5"" radius="1.25" color="#EF2D5E"></a-sphere> <a-cylinder position="1 0.75 "-3"" radius="2" height="3" color="#FFC65D"></a-cylinder> <a-plane position="0 0 "-4"" rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane> <a-sky color="#ECECEC"></a-sky> </a-scene> 
```

This made the cylinder blow up on the screen. It looked huge now compared to how it looked before. Now I wanted to try something different; I wanted to add a lot of shapes. So here is how I changed the code:
```html
<a-scene> <a-box position="1 1 3" rotation="0 45 0" color="#4CC3D9"></a-box> <a-box position="1 "-0.5" 3" rotation="0 45 0" color="#4CC3D9"></a-box> <a-box position="-2 5 "-6"" rotation="0 45 0" color="#4CC3D9"></a-box> <a-box position="3 6 4" rotation="0 45 0" color="#4CC3D9"></a-box> <a-sphere position="0 1.25 "-5"" radius="1.25" color="#EF2D5E"></a-sphere> <a-cylinder position="1 0.75 "-3"" radius="2" height="3" color="#FFC65D"></a-cylinder> <a-plane position="0 0 "-4"" rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane> <a-sky color="#ECECEC"></a-sky> </a-scene> 
```

This made everything look crazy. There were boxes everywhere. I made sure to change the positioning of the boxes so they were not just on top of each other.


[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)
