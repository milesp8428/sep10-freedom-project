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
