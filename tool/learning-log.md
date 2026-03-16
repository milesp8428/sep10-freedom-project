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

### X/X/XX:
* Text


<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
