---
layout: page
title: MyoSuite-Project1
description: Reinforcement Learning Controller for Lower Limb Standing Balance
img: assets/img/project_1.jpg
importance: 1
category: MyoSuite
related_publications: true
---
<div class="row justify-content-center">
    <div class="col-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Healthy_AP_30N.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Sarco_AP_30N.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    MyoLeg undergoing perturbation in the AP direction in healthy (left) and sarcopenia (right) cases.
</div>


Fall-related injuries due to loss of balance are detrimental to the health, independence, and quality of life among the elders (e.g. hip fractures, traumatic brain injuries). The issue is highlighted by the onset of sarcopenia in the lower limbs, an age-related condition of muscle loss that heightens the risk of falls. Our research aims to quantify the impact of sarcopenia on an individual's ability to remain stable under perturbation during bipedal stance through the advanced musculoskeletal simulation, MyoSuite.

<div class="row justify-content-center">
    <div class="col-sm-3 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/fall.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-7 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/sarco.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Sarcopenia condition: decrease in muscle volume and coordination due to aging contributes to falling.
</div>


The purpose of this study is to understanding if reinforcement learning can reproduce motions of human standing balance under sarcopenia condition. We proposed that under sarcopenia condition, baseline stability policy would lead to higher falling rates and shorter standing time under perturbation than in healthy subject.

MyoLeg is a lower limb musculoskeletal model powered by MyoSuite that allows for 80 muscle-tendon units and 20 DoFs.

<div class="row justify-content-center">
    <div class="col-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/front.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/back.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    MyoLeg powered by MyoSuite, with 10 joints, 20 DoFs, and 80 muscles-tendon units (front & left)
</div>

We employ the Proximal Policy Optimization (PPO) algorithm to train the model across both healthy and sarcopenic muscle. The PPO uses a two-hidden-layer neural network with 256 neurons and a ReLU activation function. Our reward function consists of minimizing the metabolic cost, maintaining the agent’s center of mass (CoM) within the base of support (BoS), and minimizing the pelvis position error.

<div class="row justify-content-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/PPO_Flow.jpg" title="example image" class="img-fluid rounded" %}
    </div>
</div>
<div class="caption">
    General framework for training the lower limb agent to maintain balance.
</div>
