---
permalink: /research/
title: ""
layout: single
---
# Research interests

I am deeply interested in how integrated entities can make decisions in the world. In particular, I am fascinated by how this complex capacity for agency in wholes evolves from interactions of simple parts. Evidently, the evolutionary, ecological and developmental constraints of agents will influence the types of objectives and actions they can form. Two main questions keep haunting me:
- It seems apparent that agents do things for *reasons*. All the algorithms and mechanisms we hypothesize for decision making assume certain *reasons* for behavior. In my view, it is of utmost importance we aim to understand those *reasons*, or else our algorithmic and mechanistic understanding will be skewed. In short, what are agents trying to achieve? Why and how does an agent build those **objectives**? And how do those objectives change with context? 
- If agency is an evolved trait, there should be a continuous trajectory of action abstraction. In fields like RL, the idea of action is almost a starting point, yet for me it is an end goal: how do **actions** emerge in complex systems that sustain themselves? How are action spaces formed and maintained to produce behavior? In other (more philosophical) words, where is the locus of agency and how plastic is it?

Two projects I have worked on in the past years: the Maximum Occupancy Principle and the Breadth-Depth dilemma.

<!-- 
Agency is an elusive and controversial concept. It is a given in fields like neuroscience and cognitive science, and a heresy in teleophobic fields like evolutionary biology (although more and more accepted). 
-->

## Behavior as occupancy of action-state path space
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

## Breadth-depth dilemma
The [breadth-depth dilemma](https://www.pnas.org/content/117/33/19799) is a bounded-rationality model to investigate the influence of sampling resource constraints (e.g. time, precision, compute) on decision-making strategies. We have found different regimes of optimality that depend on the amount of sampling resources, both for discrete and continuous resources. In both of these cases, the optimal number of options to sample is a (or very close to) a power law for large amount of resources. Funny things happen at the transition!
 
![](/assets/images/fig4.pdf) 

