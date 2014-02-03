---
layout: default
title: PhysicsJS
---

# Physics<span class="js">JS</span>

<div class="center">A modular, extendable, and easy-to-use physics engine for javascript</div>

<canvas id="intro-viewport" width="0" height="300">
</canvas>

**PhysicsJS is still under development (alpha version 0.5.4), and documentation
is unfinished. Feel free to use it, just be warned that the API is in flux and better
documentation is on its way!** ([Contributors and help needed](./contribute)!)

## Demos

Check out the [demo page][demos] for some sweet examples of what you can do.


## Features

* Use as an **AMD Module (requireJS)**, or **global namespace**.
* **Modular**! Only load what you need. The core library is only 31k minified.
* **Extendable**! Don't like the collision detection algorithm? Replace it with your own!
* Not tied to a specific renderer. Display it in **DOM**, **HTML5 Canvas**, or whatever...
* Easy! It's a library **written IN javascript**... not C compiled into javascript.
  The syntax is familiar for javascript developers.
* Extensions to support **points**, **circles**, and arbitrary **convex polygons**.
* Extensions to support **constant gravity**, **newtonian gravity**, **collisions**,
  and **verlet constraints**.

## What about 3D?

There are quite a few wonderful 3D JS Physics engines available, so 2D was the first priority
for PhysicsJS... however, due to the way in which PhysicsJS was built it should be quite
possible to create a 3D fork. It is one of my long-term goals.

[demos]: ./examples


<script>require(['homepage-demo']);</script>
