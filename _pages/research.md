---
permalink: /research/
title: ""
layout: single
---

# Behavior as occupancy of action-state path space
<!---


<div class="row">
  <div class="column left">
-->



 In theories of behavior, it is usually assumed that agents maximize reward. From an algorithmic point of view, this makes sense: reward is any measure of goals that agents are interested in achieving. Its source can be external (e.g. training a robot to do something), or internal (e.g. homeostasis) to the agent. However, inferring reward signals from natural behavior and designing reward signals for artifical agents can be problematic. 
 
 In this work, we propose a simple principle of behavior: occupying action-state path space. "Reward" in the usual sense becomes a means to achieve this goal, conceptualizing it as transitions between internal states. From this principle, we obtain diverse, complex behaviors that simple reward maximizing agents with endowed variability do not display. See [publications](/publications) for more information.
 
<figure class="video_container">
<video width="100%" preload autoplay loop muted>
  <source src="/assets/animations/Video5.mp4" type="video/mp4" />
</video>
</figure>

# Breadth-depth dilemma
The [breadth-depth dilemma](https://www.pnas.org/content/117/33/19799) is a bounded-rationality model to investigate the influence of sampling resource constraints (e.g. time, precision, compute) on decision-making strategies. We have found different regimes of optimality that depend on the amount of sampling resources, both for discrete and continuous resources. In both of these cases, the optimal number of options to sample is a (or very close to) a power law for large amount of resources. Funny things happen at the transition!
 
![](/assets/images/fig4.pdf) 

