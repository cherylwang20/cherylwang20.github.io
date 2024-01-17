---
layout: page
title: MyoSuite-Project1
description: Reinforcement Learning Controller for Lower Limb Standing Balance
img: assets/img/project_1.jpg
importance: 1
category: Mechanical Engineering
related_publications: true
---


The purpose of this study is to understanding if reinforcement learning can reproduce motions of human standing balance under sarcopenia condition. We proposed that under sarcopenia condition, baseline stability policy would lead to higher falling rates and shorter standing time under perturbation than in healthy subject.

MyoLeg is a lower limb musculoskeletal model powered by MyoSuite that allows for 80 muscle-tendon units and 20 DoFs.

<div class="row">
    <div class="col-sm-3 offset-sm-3 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/front.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-3 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/back.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    MyoLeg powered by MyoSuite, with 10 joints, 20 DoFs, and 80 muscles-tendon units (front & left)
</div>


Using the MyoSuite as the Musculoskeletal Simulation and RL controller trained using PPO policy, we train the agent to maintain balance under a perturbed external force between 0 - 50N.
