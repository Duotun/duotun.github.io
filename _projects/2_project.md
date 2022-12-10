---
layout: page
title: Shader Collection
description: Shaders in Unity3D
img: assets/img/window.png
importance: 2
category: Graphics & Shader
---
[Code](https://github.com/Duotun/Shader-Collections)

"Rainy Window Effect" is implemented with GLSL in Unity3D. Core implementation is highly related to fragement shader, mipmap, transparency and blurred effects, following [this art tutorial](https://www.shadertoy.com/view/ltffzl).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Droplet_leaves.gif" title="fluid image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/RainyWindow_leaves.gif" title="fluid image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, Droplets Only; On the Right, Droplets + Window Effect
</div>


"Depth Shader" is achieved by utilize the depth information of depth camera and used for blending real-world capturing and virtual scenes.
<div class="row align-items-center">
    <div class="col align-self-center">
        {% include figure.html path="assets/img/BlendReality.gif" title="fluid image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    Users could view both objects in real and virtual world with the VR headset. 
</div>


"Dissolve Shader" is programmed with HLSL in Unity3D by following [Febucci's great tutorial](https://www.febucci.com/2018/09/dissolve-shader/).
<div class="row align-items-center">
    <div class="col align-self-center">
        {% include figure.html path="assets/img/dissolveShader.gif" title="fluid image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    Meshes could be dissolved with input control.
</div>
