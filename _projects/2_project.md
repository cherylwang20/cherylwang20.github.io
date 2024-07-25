---
layout: page
title: RL Chemist
description: A RL framework with pure vision input to operate in a chemistry lab
img: assets/img/rl-chemist1.png
importance: 2
category: RL Chemist
related_publications: true
---

In this project, we are interested in developing a controller for UR10e robotics arm relying on vision based reinforcement learning to achieve simple pick & place tasks. We have created a suite of transparent objects using [Blender](https://www.blender.org/), and converting it to mjcf files using the package [obj2mjcf](https://github.com/kevinzakka/obj2mjcf/tree/main).



<div class="row justify-content-center">
    <div class="col-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/rl-chemist2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/rl-chemist2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A collection of the available objects to be used as within MuJoCo simulation for pick & place tasks. 
</div>