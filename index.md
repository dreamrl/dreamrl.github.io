---
title: 'Dream to Control: Learning Behaviors by Latent Imagination'
layout: default
---

# Abstract

<div class="abstract">
Learned world models summarize an agent’s experience to facilitate learning
complex behaviors. While learning world models from high-dimensional sensory
inputs is becoming feasible through deep learning, there are many potential
ways for deriving behaviors from them. We present Dreamer, a reinforcement
learning agent that solves long-horizon tasks from images purely by latent
imagination. We efficiently learn behaviors by propagating analytic gradients
of learned state values back through trajectories imagined in the compact state
space of a learned world model. On 20 challenging visual control tasks, Dreamer
exceeds existing approaches in data-efficiency, computation time, and final
performance.
</div>

# Behaviors Learned by Dreamer

<div class="figure-grid">
<figure><figcaption>Cheetah Run</figcaption><img src="/assets/behavior/dmc-cheetah-run.gif"/></figure>
<figure><figcaption>Hopper Hop</figcaption><img src="/assets/behavior/dmc-hopper-hop.gif"/></figure>
<figure><figcaption>Walker Run</figcaption><img src="/assets/behavior/dmc-walker-run.gif"/></figure>
<figure><figcaption>Quadruped Run</figcaption><img src="/assets/behavior/dmc-quadruped-run.gif"/></figure>
<figure><figcaption>Cup Catch</figcaption><img src="/assets/behavior/dmc-cup-catch.gif"/></figure>
<figure><figcaption>Cartpole Sparse</figcaption><img src="/assets/behavior/dmc-cartpole-swingup-sparse.gif"/></figure>
<figure><figcaption>Pendulum Swingup</figcaption><img src="/assets/behavior/dmc-pendulum-swingup.gif"/></figure>
<figure><figcaption>Acrobot Swingup</figcaption><img src="/assets/behavior/dmc-acrobot-swingup.gif"/></figure>
<figure><figcaption>Reacher Easy</figcaption><img src="/assets/behavior/dmc-reacher-easy.gif"/></figure>
<figure><figcaption>Reacher Hard</figcaption><img src="/assets/behavior/dmc-reacher-hard.gif"/></figure>
<figure><figcaption>Finger Spin</figcaption><img src="/assets/behavior/dmc-finger-spin.gif"/></figure>
<figure><figcaption>Finger Turn Hard</figcaption><img src="/assets/behavior/dmc-finger-turn-hard.gif"/></figure>
</div>

# Atari and DMLab with discrete actions

<div class="figure-grid">
<figure><figcaption>Fishing Derby</figcaption><img src="/assets/behavior/atari-fishing-derby.gif"/></figure>
<figure><figcaption>Ice Hockey</figcaption><img src="/assets/behavior/atari-ice-hockey.gif"/></figure>
<figure><figcaption>Kung Fu Master</figcaption><img src="/assets/behavior/atari-kungfu-master.gif"/></figure>
<figure><figcaption>Assault</figcaption><img src="/assets/behavior/atari-assault.gif"/></figure>
<figure><figcaption>Boxing</figcaption><img src="/assets/behavior/atari-boxing.gif"/></figure>
<figure><figcaption>Hero</figcaption><img src="/assets/behavior/atari-hero.gif"/></figure>
<figure><figcaption>Freeway</figcaption><img src="/assets/behavior/atari-freeway.gif"/></figure>
<figure><figcaption>Frostbite</figcaption><img src="/assets/behavior/atari-frostbite.gif"/></figure>
<figure><figcaption>Montezuma</figcaption><img src="/assets/behavior/atari-montezuma.gif"/></figure>
<figure><figcaption>Pong</figcaption><img src="/assets/behavior/atari-pong.gif"/></figure>
<figure><figcaption>Tennis</figcaption><img src="/assets/behavior/atari-tennis.gif"/></figure>
<figure><figcaption>Collect Objects</figcaption><img src="/assets/behavior/dmlab-collect.gif"/></figure>
</div>

# Multi-Step Video Predictions

<center style="margin-bottom: 1em;">
Top: Holdout Sequences
<span style="display: inline-block; width: 3em;"></span>
Middle: Predictions
<span style="display: inline-block; width: 3em;"></span>
Bottom: Differences
</center>

<figure><img src="/assets/pred/quadruped.gif" /></figure>
<figure><img src="/assets/pred/fishing-derby.gif" /></figure>
<figure><img src="/assets/pred/hero.gif" /></figure>
<figure><img src="/assets/pred/collect.gif" /></figure>

# Read the Paper for Details [[PDF]](https://arxiv.org/pdf/1912.01603.pdf)

<div class="pages">
<img src="/assets/pages/1.png" />
<img src="/assets/pages/2.png" />
<img src="/assets/pages/3.png" />
<img src="/assets/pages/4.png" />
<img src="/assets/pages/5.png" />
<img src="/assets/pages/6.png" />
<img src="/assets/pages/7.png" />
<img src="/assets/pages/8.png" />
<img src="/assets/pages/9.png" />
</div>
