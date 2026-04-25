# Entry 5
##### 4/20/26

<h1> Content</h1>
The tool I chose for the Freedom Project was A-Frame. Within the time given to me, I have learned a lot about my tool. One of the things that I have learned is how to use A-Frame more effectively, how to make objects move, and how to put scenes together in a way that resembles something. One of the thing sthat made was a cabin. I already knew what I wanted to look like because I had scheduled it out. This is what the code looks like:

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
I wanted to incorporate ideas from my part B. One of the ideas was to make solar panel windows. I thought it would be a cool idea to add solar panel windows to this cabin. This is what the code looks like:
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
These windows kind of resemble what a solar panel looks like while still keeping them looking like a window. One of my classmates was showing me his project, and he was editing his project while viewing it. He told me he was doing this by doing "Ctrl Alt I," but this doesn't put the code in, so it's good for doing something quick, but shouldn't be used for the entire project. I am also trying to make more of my code because I think it saves me a lot of time when it comes to looking through my code and referring back to it. I thought it would be cool to make the solar panel windows rotat but this was complicated. I copied and pasted some code from the A-Frame website, but I am still trying to figure out how this works. 

<h1> Sources </h1>
I tried out a few different sources, but what I found to be the most helpful was using [aframe.io](https://aframe.io/). Because it gave me starter code and showed me how different aspects of A-Frame work. This is how I got the starter code for moving objects in A-Frame. Sometimes I will watch YouTube videos, but I haven't found a singular one that was very helpful. I will also ask my classmates for advice when I'm confused or ill, or look it up.

<h1>Skills</h1>
One of the skills that developed was learning how to work with a deadline. This is a very useful skill because in school you always have to work with a deadline, and knowing how to maximize my time helps a lot.

Another skill I learned was how to think creatively. Being able to think creatively can help in almost every aspect of life. Wether if its when you want to make something new or offer someone an idea, being able to think creatively or outside the box can really help.

[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
