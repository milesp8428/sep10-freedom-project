# Tool Learning Log

## Tool: **A-Frame**

---

### 3/16/26:
* The way to use the position is to think of it like x y, and z coordinates
  * This also works for rotation
```html
<a-box
  position="1 0.5 3"
  rotation="0 45 0"
  color="#4CC3D9">
</a-box>


<a-cone
  position="1 1.5 3"
  rotation="0 90 0"
  segments-radial="4"
  radius-bottom="1"
  height="1"
  color="red">
</a-cone>
```
* This will make the cone on the box making it resemble a house
    * This is the website I used to learn about A-Frame [medium.com](https://medium.com/immersion-for-the-win/relative-positioning-in-a-frame-d839fc0e3249)
* What other shapes are there?
  * I asked AI to make me a list of shapes that I can use. This is what it came up with:
    * 3D (Solid) Shapes
    * Box: <a-box> — Used for cubes, walls, or rectangular prisms.
    * Sphere: <a-sphere> — Creates a spherical or polyhedron shape.
    * Cylinder: <a-cylinder> — Ideal for tubes and curved surfaces.
    * Cone: <a-cone> — A shape with a circular base and a pointed top.
    * Torus: <a-torus> — A donut-like ring shape.
    * Torus Knot: <a-torus-knot> — A complex, knotted ring. 

    * Polygonal Solids
    * Tetrahedron: <a-tetrahedron> — A four-faced triangular pyramid.
    * Octahedron: <a-octahedron> — An eight-faced solid.
    * Dodecahedron: <a-dodecahedron> — A twelve-faced solid.
    * Icosahedron: <a-icosahedron> — A twenty-faced solid. 

    * 2D (Flat) Shapes
    * Plane: <a-plane> — A flat surface, often used for floors or walls.
    * Triangle: <a-triangle> — A simple 2D triangle.
    * Circle: <a-circle> — A flat 2D disk.
    * Ring: <a-ring> — A flat 2D circle with a hole in the center. 

    * Specialty Primitives
    * Sky: <a-sky> — Adds a background color or a 360° "photo" to the entire scene.
    * Curved Image: <a-curvedimage> — Displays an image on a curved surface.
 * I contiuned to add to the house I was making
  * I added a door and a floor this is what the code looks like:
    ```html
    <a-plane
    position="0 0 0"
    rotation="-90 0 0"
    width="20"
    height="20"
    color="#7BC8A4">
    </a-plane>


    <a-box
    position="1 0.5 3"
    rotation="0 45 0"
    color="#4CC3D9">
    </a-box>


    <a-cone
    position="1 1.5 3"
    rotation="0 90 0"
    segments-radial="4"
    radius-bottom="1"
    height="1"
    color="red">
    </a-cone>
    <a-plane
      position="1.36 0.4 3.36"
      rotation="0 45 0"
      width="0.4"
      height="0.7"
      color="#5D4037">
    </a-plane>
    
    
    <a-plane
      position="0.64 0.6 3.36"
      rotation="0 90 0"
      width="0.3"
      height="0.3"
      color="#FFFFFF">
    </a-plane>
    ```
* Next, I think that I will make trees in front of the house, or i might try to make a pathway.  

### 3/29/26:
* [YouTube Video](https://www.youtube.com/%20%20%20?v=3JePvWQWUVs)
 * This YouTube video just went through the basics, but it did give me some inspiration on what I can make with A-Frame.
 * After watching this video, I saw that the person who made it had a playlist of different videos that I could watch that went more in-depth about more specific things.
* Last week, I made a small house; it was just a cone on top of a box. I decided that it would look cool if I made multiple houses to make it look like a mini town.
* To do this i had to copy and paste the code of the origanal houseand then I would change the x position of the house. This made it so the houses looked the same, but they were just moved over a little bit. Then I repeated this 2 more times. Its importantt to change both pieces of the house's x coordinate by the same amount. This is what my code looked like:
```html
<!DOCTYPE html>
<html>
    <head>
        <!-- Required meta tags -->
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">

        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" />
        <link href="style.css" rel="stylesheet" type="text/css" />
        <style>
            /* CSS */

        </style>

        <title>Title</title>
    </head>
    <body>
        <!-- HTML -->


        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
        <!-- <script src="script.js"></script> -->
        <script>
            // JS


        </script>
    </body>
</html>

<html>
  <head>
    <script src="https://aframe.io/releases/1.7.1/aframe.min.js"></script>
  </head>
  <body>
  <html>
  <head>
    <script src="https://aframe.io/releases/1.7.1/aframe.min.js"></script>
  </head>
  <body>
    <a-scene>
  <!-- The Ground (Floor) -->
<a-plane
  position="0 0 0"
  rotation="-90 0 0"
  width="20"
  height="20"
  color="#7BC8A4">
</a-plane>


<a-box
  position="-1 0.5 3"
  rotation="0 45 0"
  color="#4CC3D9">
</a-box>


<a-cone
  position="-1 1.5 3"
  rotation="0 90 0"
  segments-radial="4"
  radius-bottom="1"
  height="1"
  color="red">
</a-cone>
<a-plane
  position="-1.36 0.4 3.36"
  rotation="0 45 0"
  width="0.4"
  height="0.7"
  color="#5D4037">
</a-plane>


<!--2-->
<a-box
  position="1 0.5 3"
  rotation="0 45 0"
  color="#4CC3D9">
</a-box>


<a-cone
  position="1 1.5 3"
  rotation="0 90 0"
  segments-radial="4"
  radius-bottom="1"
  height="1"
  color="red">
</a-cone>
<a-plane
  position="1.36 0.4 3.36"
  rotation="0 45 0"
  width="0.4"
  height="0.7"
  color="#5D4037">
</a-plane>

<!--3-->
<a-box
  position="-3 0.5 3"
  rotation="0 45 0"
  color="#4CC3D9">
</a-box>


<a-cone
  position="-3 1.5 3"
  rotation="0 90 0"
  segments-radial="4"
  radius-bottom="1"
  height="1"
  color="red">
</a-cone>
<a-plane
  position="-3.36 0.4 3.36"
  rotation="0 45 0"
  width="0.4"
  height="0.7"
  color="#5D4037">
</a-plane>

<!--4-->
<a-box
  position="-5 0.5 3"
  rotation="0 45 0"
  color="#4CC3D9">
</a-box>


<a-cone
  position="-5 1.5 3"
  rotation="0 90 0"
  segments-radial="4"
  radius-bottom="1"
  height="1"
  color="red">
</a-cone>



   </a-scene>
  </body>
</html>
  </body>
</html>
```
 * As you can see, there are 4 houses all in a diagonal arrangement.
 * Now I have made another house. But I made it diffrent form the other ones that I was making before. This one was bigger and had different colors, but the major difference is that I made walls, so instead of having one big box i made it more realistic to a real house where there would be walls. What I learned is that you can use the depth and the width to flip or rotate the walls. Here is the code that I made:
```html
<a-box
    position="5 .5 -3"
    width="2"
    height="3"
    depth="0.5"
    color="#4CC3D9">
  </a-box>
<a-box
    position="5 .5 -1"
    width="2"
    height="3"
    depth="0.5"
    color="#4CC3D9">
  </a-box>

<a-box
    position="6 .5 -2"
    width=".5"
    height="3"
    depth="2.5"
    color="#4CC3D9">
  </a-box>

  <a-box
    position="4 .5 -2"
    width=".5"
    height="3"
    depth="2.5"
    color="#4CC3D9">
  </a-box>

<a-cone
  position="5 2.95 -2"
  rotation="0 90 0"
  segments-radial="6"
  radius-bottom="2"
  height="2"
  color="black">
</a-cone>

<a-box
    position="4 .5 -2"
    width=".5"
    height="2"
    depth="1"
    color="brown">
  </a-box>
```
 * Since the topic I chose for my freedom project is architecture, I have made some sketches of different houses and structures. I want to try to make a sketch I made of a cabin in aframe next.


<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->

### 4/5/26:
 In my last learning log i said that I wanted to make one of my drawings in A-Frame. This ended up being a lot harder than I thought it would be, and I couldn't add all of the little details that I wanted to. This is want the code looks like:
 ```html
 <!--right side-->
  <a-box
    position="39 1 -2"
    width=".25"
    height="4"
    depth="3"
    color="grey">
  </a-box>

  <a-box
    position="35 1 -2"
    width=".25"
    height="4"
    depth="3"
    color="grey">
  </a-box>

  <a-box
    position="37 1 -.5"
    width="4.25"
    height="4"
    depth=".25"
    color="grey">
  </a-box>

  <a-box
    position="37 1 -3.5"
    width="4.25"
    height="4"
    depth=".25"
    color="grey">
  </a-box>



  <!-- Right Roof Panel -->
  <a-box
    position="38 3.5 -2.5"
    scale="2.5 0.1 4.5"
    rotation="0 0 -30"
    color="grey"
  ></a-box>



   <a-box
    position="36 3.5 -2.5"
    scale="2.5 0.1 4.5"
    rotation="0 0 30"
    color="grey"
  ></a-box>



  <!--  Triangle -->
  <a-triangle color="grey" vertices=" 9 -9 9" position="37 3.5 -.5"
  scale="4 1.5 3.5"></a-triangle>

<!--back part-->

  <a-box
    position="39 1 -5"
    width=".25"
    height="4"
    depth="3"
    color="grey">
  </a-box>

  <a-box
    position="25 1 -5"
    width=".25"
    height="4"
    depth="3"
    color="grey">
  </a-box>

  <a-box
    position="33 1 -3.5"
    width="12"
    height="4"
    depth=".25"
    color="grey">
  </a-box>

  <a-box
    position="32 1 -6.5"
    width="14"
    height="4"
    depth=".25"
    color="grey">



<!--roof-->
  </a-box>
<a-box
    position="32 3.5 -6"
    scale="2.5 0.1 15"
    rotation="0 90 -30"
    color="grey"
  ></a-box>



   <a-box
    position="32 3.5 -4"
    scale="2.5 0.1 15"
    rotation="0 90 30"
    color="grey"
  ></a-box>










  <!--left side-->
  <a-box
    position="29 1 -2"
    width=".25"
    height="4"
    depth="3"
    color="grey">
  </a-box>

  <a-box
    position="25 1 -2"
    width=".25"
    height="4"
    depth="3"
    color="grey">
  </a-box>

  <a-box
    position="27 1 -.5"
    width="4.25"
    height="4"
    depth=".25"
    color="grey">
  </a-box>

  <a-box
    position="27 1 -3.5"
    width="4.25"
    height="4"
    depth=".25"
    color="grey">
  </a-box>



  <!-- Right Roof Panel -->
  <a-box
    position="28 3.5 -2.5"
    scale="2.5 0.1 4.5"
    rotation="0 0 -30"
    color="grey"
  ></a-box>



   <a-box
    position="26 3.5 -2.5"
    scale="2.5 0.1 4.5"
    rotation="0 0 30"
    color="grey"
  ></a-box>
 <!-- Basic Triangle -->
  <a-triangle color="grey" vertices=" 9 -9 9" position="25 3.5 -5"
  scale="4 1.5 3.5"   rotation="0 90 0" ></a-triangle>


  <!-- Basic Triangle -->
  <a-triangle color="grey" vertices=" 9 -9 9" position="27 3.5 -.5"
  scale="4 1.5 3.5"></a-triangle>

 ```
Something that has been makeing making things in A-Frame has been having to change the coordinates a lot because I already have stuff at the origin. So I think that for my next learning log, I will just make another file. I still want to continue to work on the cabin, so I'm going to copy and paste the code I worked on this week into the new file. Next, I'm going to add more details and change the colors so the entire house is not grey.

### 4/13/26:
As part of my plan, I wanted to change the color of the cabin from all grey to the colors of an actual cabin. First, I knew that I wanted the walls to be brown as if they were wood. I made the color brown, but this didn't look good, so I changed it to dark brown. This looked better. I originally made the roof brown. This looked treible then I turned it brown. This looked bad. I looked up what cabins look like, and a lot of the cabins had green roofs, so I made the roof green. This looked good. This is what the code looked like:
```html
  <a-box
    position="39 1 -2"
    width=".25"
    height="4"
    depth="3"
    color="#654321">
  </a-box>

  <a-box
    position="35 1 -2"
    width=".25"
    height="4"
    depth="3"
    color="#654321">
  </a-box>

  <a-box
    position="37 1 -.5"
    width="4.25"
    height="4"
    depth=".25"
    color="#654321">
  </a-box>

  <a-box
    position="37 1 -3.5"
    width="4.25"
    height="4"
    depth=".25"
    color="#654321">
  </a-box>



  <!-- Right Roof Panel -->
  <a-box
    position="38 3.5 -2.5"
    scale="2.5 0.1 4.5"
    rotation="0 0 -30"
    color="green"
  ></a-box>



   <a-box
    position="36 3.5 -2.5"
    scale="2.5 0.1 4.5"
    rotation="0 0 30"
    color="green"
  ></a-box>



  <!--  Triangle -->
  <a-triangle color="#654321" vertices=" 9 -9 9" position="37 3.5 -.5"
  scale="4 1.5 3.5"></a-triangle>

<!--back part-->

  <a-box
    position="39 1 -5"
    width=".25"
    height="4"
    depth="3"
    color="#654321">
  </a-box>

  <a-box
    position="25 1 -5"
    width=".25"
    height="4"
    depth="3"
    color="#654321">
  </a-box>

  <a-box
    position="33 1 -3.5"
    width="12"
    height="4"
    depth=".25"
    color="#654321">
  </a-box>

  <a-box
    position="32 1 -6.5"
    width="14"
    height="4"
    depth=".25"
    color="#654321">



<!--roof-->
  </a-box>
<a-box
    position="32 3.5 -6"
    scale="2.5 0.1 15"
    rotation="0 90 -30"
    color="green"
  ></a-box>



   <a-box
    position="32 3.5 -4"
    scale="2.5 0.1 15"
    rotation="0 90 30"
    color="green"
  ></a-box>










  <!--left side-->
  <a-box
    position="29 1 -2"
    width=".25"
    height="4"
    depth="3"
    color="#654321">
  </a-box>

  <a-box
    position="25 1 -2"
    width=".25"
    height="4"
    depth="3"
    color="#654321">
  </a-box>

  <a-box
    position="27 1 -.5"
    width="4.25"
    height="4"
    depth=".25"
    color="#654321">
  </a-box>

  <a-box
    position="27 1 -3.5"
    width="4.25"
    height="4"
    depth=".25"
    color="#654321">
  </a-box>



  <!-- Right Roof Panel -->
  <a-box
    position="28 3.5 -2.5"
    scale="2.5 0.1 4.5"
    rotation="0 0 -30"
    color="green"
  ></a-box>



   <a-box
    position="26 3.5 -2.5"
    scale="2.5 0.1 4.5"
    rotation="0 0 30"
    color="green"
  ></a-box>
 <!-- Basic Triangle -->
  <a-triangle color="#654321" vertices=" 9 -9 9" position="25 3.5 -5"
  scale="4 1.5 3.5"   rotation="0 90 0" ></a-triangle>


  <!-- Basic Triangle -->
  <a-triangle color="#654321" vertices=" 9 -9 9" position="27 3.5 -.5"
  scale="4 1.5 3.5"></a-triangle>


<a-box
    position="32 0 -3.5"
    scale="2 5 1"
    color=" brown"></a-box>
```
As you can see, the cabin is now colored in. Along with colering this, I also made a door, and I made the door brown. Next, I added windows, then realized that I could incorporate my part B into it. The aspect of my part B that I wanted to incorporate was solarpanlal windos thses windoes can rotate to track the sun and can open and close. To show this, I made the windows in the act of rotating. This is what the code looked like:"
```html
<!--window1-->


  <a-box
    position="27 1.45 .1"
    scale="2 2 .15"
    color="#000080"
    rotation="-30 0 0"
    ></a-box>

     <a-box
    position="27 1.5 .1"
    scale=".25 2 .25"
    color="grey"
    rotation="-30 0 0"
    ></a-box>


     <a-box
    position="27 1.75 -.1"
    scale="2 .25 .25"
    color="grey"
    rotation="-30 0 0"
    ></a-box>

     <a-box
    position="27 1.15 .25"
    scale="2 .25 .25"
    color="grey"
    rotation="-30 0 0"
    ></a-box>

<!--window2-->
    <a-box
    position="37 1.45 .1"
    scale="2 2 .15"
    color="#000080"
    rotation="-30 0 0"
    ></a-box>

     <a-box
    position="37 1.5 .1"
    scale=".25 2 .25"
    color="grey"
    rotation="-30 0 0"
    ></a-box>


     <a-box
    position="37 1.75 -.1"
    scale="2 .25 .25"
    color="grey"
    rotation="-30 0 0"
    ></a-box>

     <a-box
    position="37 1.15 .25"
    scale="2 .25 .25"
    color="grey"
    rotation="-30 0 0"
    ></a-box>
```
These windows kind of resemble what a solar panel looks like while still keeping them looking like a window. One of my classmates was showing me his prject he was editing his project while viewing it. He told me he was doing this by doing "Ctrl Alt I," but this doesn't put the code in, so it's good for doing something quick, but shouldn't be used for the entire project. I am also trying to make more of my code because I think it saves me a lot of time when it comes to looking through my code and referring back to it. I thought it would be cool to make the solar panel windows rotat but this was complicated i copy and pasted some code from the A-Frame website, but I am still trying to figure out how this works. In my planing i wanted to make grases and I wanted to transform the surroundings. This was a lot harder then i thought it would be at frist i wanted to just put flowers and grass in there manually. resied how long this would take, and fake it would look so I decided not to do it that way, then I looked at how to add grass to your A-Frame code, and what came up was Techerpack. I put this teacher's pack into my code, and it looked bad. not in a way where it was not aesthetically pleasing, but I simply didn't work it, glitched with the ground, and looked really bad, so I deleted it. I don't want to give up on adding this, but it's a lot of work to figure out right now, and when I have more time, this is what I want to work on.

