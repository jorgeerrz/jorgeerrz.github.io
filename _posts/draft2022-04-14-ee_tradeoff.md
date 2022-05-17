---
layout: single
title: The problem with the Exploration-Exploitation tradeoff
comments: true
---

The Exploration-Exploitation (EE) tradeoff is a widely used framework to study how agents in general navigate uncertain environments in order to maximize rewards. The standard example is the restaurant story in your city: Do you stick with the restaurant you love, knowing exactly what you will get (exploitation), or do you switch it up and try any of those new restaurants you've been meaning to try (exploration)? Another popular example comes from multiarmed bandits. Imagine you are at a casino and you are playing some slot machines. Each one has a particular payoff, some are good on average, some are bad on average. What is the best play strategy to earn as much money as you can? In other words, how many times do you need to play each machine?

It is obvious to think that this tradeoff makes a lot of sense, we've all been there maximizing our happiness or time/money investments. In reality, trying to resolve this tension only makes sense when you have a particular objective in mind: maximizing rewards. This is the main issue with this way of thinking, because rewards are arbitrary.

## What the Exploration-Exploitation tradeoff gets us

Clearly, the EE tradeoff is extremely useful to study single tasks: When you have a particular objective in mind (maximizing happiness from food, or money from slot machines), then the task is determined and you can go ahead and try to find your way to the optimal tradeoff between exploring and exploiting the uknown options at hand.

This, in fact, is the paradigmatic state of the field of computational/cognitive neuroscience. Model organisms perform "cognitive tasks" and a bunch of scientists stick electrodes and/or build network models to study the electrical activity in the nervous system to try to find correlates of "cognitive functions". By focusing on single tasks, and thirsty animals willing to trade food for thought, literally, one can get a glimpse of the mechanisms that are used by and the phenomena observable in the neural networks when the whole animal performs the task. This is mostly due thanks to the assumption that the animal is doing **one** single thing --namely maximizing the reward modulated by the experimenter, and thus attempting to perform the task. When the animal

In particular experiments that focus on how animals explore versus how they exploit, then the whole thing is self-consistent and you can "catch" moments when the animal is exploiting (choosing the current "best" option) versus when it is exploring (ref). This can provide a picture of how organisms explore their environment, which is a big component of adaptive, intelligent behavior.


## Why it is problematic

Albeit useful, I argue here that the EE tradeoff pains a biased picture that is only a piece of the puzzle, and a fresh perspective is needed to think in more ecological terms what the animals are doing.

### The tyranny of the single task

First off, the vocabulary used to determine the cognitive functions in computational, cognitive and systems neuroscience is probably outdated and it has been righteously protested against (see Paul Cisek's [phylogenetic refinement project](https://link.springer.com/article/10.3758/s13414-019-01760-1) or György Buzsáki's book [The Brain from Inside Out](https://buzsakilab.com/wp/publications/books/)). Secondly, it might be naive to think that the animal has the same representation of the task (if any) as us, which we contentiously assume when building our models.

### The reward maximization hypothesis

It is quite natural for us humans to extract intentionality into seemingly autonomous agents. This ability of forming representations of goals permits any autonomous, intelligent agent to excel at a particular thing for a short amount of time. This intuiton is baked in the whole compuational neuroscience endeavour, and it sometimes can be harmful. For example, when rodents perform an auditive discrimination task, and they are not "rational", we assume they are suboptimal (ref), or that they lapse (ref), or even that these lapses have an objective (ref). All these results stand on top of the big reward maximization hypothesis without questioning it, and it biases our interpretations of animal behavior.

One could argue that the ability to abstract and form goals and subgoals is one of the hallmarks of intelligence, so we must be in the right track by focusing on single tasks that animals use to maximize reward. *This* in fact is the trap of the EE tradeoff. When trying to understand autonomous intelligence, I believe it is intractable to list or infer all of the tasks that an organism faces, especially when that organism endogenously creates subgoals. Not only studying single tasks is hopeless to understand intelligence, but it is also deeply unsatisfying: Why do I want to maximize happiness from food? Why do I want to maximize the money I get from casino slot machines?

Following the usual story from this question almost always ends up at the survival dead end: Well, I would like to maximize money or happiness because that helps me survive (and perhaps pass my genetic or cultural material eventually). Ok, and why is that? Some folks would argue that this is simply **not** the question they are trying to answer, which I guess is fine. However, I argue that the particular objective in mind matters not only to the understanding of a particular system, but also the actual decision making strategies you can find.

 This is extremely relevant to current efforts from AI research to create "Artificial General Intelligence". There is no doubt that the recent accomplishments from Deep Reinforcement Learning are an amazing tool for us humans (see [AlphaFold](https://www.nature.com/articles/s41586-021-03819-2) or the [nuclear fusion plasma control](https://www.deepmind.com/blog/accelerating-fusion-science-through-learned-plasma-control), for recent examples). However, trying to extrapolate externally crafted reward signals into an artificial agent will not get you artificial general intelligence, almost by definition.

## Then what?

So what is a viable alternative? The key, in my view, lies on the organism itself. What is intelligence without life (or [*lyfe*](https://www.mdpi.com/2075-1729/10/4/42)), anyways? I won't fully go in that direction, but I think there is something to be said about that. Trying to understand natural intelligence from such a high level of description (e.g. a whole multicellular organism that evolved for billions of years in conjuction with other evolving creatures, "performing" a "cognitive task") is almost doomed to fail without trying to understand what life is *trying* to do. I don't offer a theory of everything, of course, but shifting our attention towards a more fundamental understanding of agency (including all types of interacting, living organisms) will surely bring a fresh perspective into fields such as systems neuroscience or decision making (see Cisek and Buzsáki, above).

My take is that, while the EE tradeoff is a useful abstraction, we should never let it out of our sight that it is **our** artificial abstraction. As such, it offers a limited view of natural intelligence, one that requires some additional external intelligence to abstracts things such as "task", "reward", "memory", etc.
