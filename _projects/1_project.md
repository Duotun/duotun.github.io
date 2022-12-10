---
layout: page
title: Fluid Simulation
description: 2D Interactive Fluid Simulation
img: assets/img/fluid.png
importance: 1
category: Graphics & Shader
---
[Code](https://github.com/Duotun/My-Taichi-Practice)

This project is implemented with [TAICHI](https://taichi.graphics/). The core idea is "BFECC For Advection" and for projecction part, I implemented with Jacobi and Conjugate methods as a comparison.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Interactive Fluid.gif" title="fluid image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Interactive_Fluid_cg.gif" title="fluid image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, Jacobi (40 FPS); On the Right, Conjugate Gradient (11 FPS)
</div>


Reference \\
1) [Fluid Simulation of Computer Graphics](https://www.amazon.com/Simulation-Computer-Graphics-Robert-Bridson/dp/1568813260) \\
2) [Taichi Example Code - Stable Fluid](https://github.com/taichi-dev/taichi/blob/3050606b44a64e3e1070835b7bfe22eee39a00a1/examples/stable_fluid.py)



