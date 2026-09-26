---
layout: post
title: "Time Flies As You Get Older"
---

The idea is usually called **subjective time acceleration** effect. One intuitive explanation is the proportional theory of time. When you are 5, one year is 20% of your entire life. At 25, it's 4%; at 50, it's 2%. So each year represents a progressively smaller fraction of your accumulated experience. 

But psychologists generally think memory and novelty are at least as important. Childhood and early adulthoold contain lots of firsts - first school, first relationships, new cities, new jobs, new experiences. The brain creates many distinctive memories. Later, life can become more repetitive, so months containing similar routines get compressed when you look back.

To stay younger, you have to keep on creating novel memories.

### A simple mathematical model to quantify things

Assume subjective time grows logarithmically with age. 

Let chronlogical age be *t*, and subjective accumulated time be:

$$
S(t) = k \ln(t)
$$

where *k* is a scaling constant.

The subjective length of one year when you are age *t* is then:

$$
\Delta S(t) = S(t+1) - S(t)
$$

so:

$$
\Delta S(t) = k \ln\left(\frac{t+1}{t}\right)
$$

For reasonably large *t*,

$$
\ln\left(1 + \frac{1}{t}\right) \approx \frac1t
$$

so the simple intuition becomes:

$$
\text{perceived length of a year} \propto \frac1{\text{age}}
$$

### What this predicts
Suppose we define how long an year feels at age 10 as 1 subjective year.

Then the relative perceived length of 1 year is:

$$
R(t) = \frac{\ln((t+1)/t)}{\ln(11/10)}
$$

This is approximately

| Age | Relative perceived length of 1 year |
|-----|-------------------------------------|
|5     |1.91x                               |
|10    |1.00x                               |
|15    |0.68x                               |
|20    |0.51x                               |
|26    |0.40x                               |
|30    |0.34x                               |
|40    |0.26x                               |
|50    |0.21x                               |
|60    |0.17x                               |
|80    |0.13x                               |

According to this model, an year at 50 feels roughly one-fifth as long as an year felt at age 10.

### Now if you add the novelty factor

Novelty is less about the quantity of activities and more about creating distinct chapters. One six-month project of learning, struggling, meeting people and progressing could generate far more novelty than fifty interchangeable nights out.

We introduce a novelty coefficient, *N(t)*

$$
dS = \frac{N(t)}{t} dt
$$

Therefore:

$$
S(t_1,t_2) = \int_{t_1}^{t_2}\frac{N(t)}{t}dt
$$

Where:
- *t* = age
- N(t) = 1 = normal/routine life
- N(t) > 1 = lots of novelty and distinct memories
- N(t) < 1 = highly repetitive period

This gives us:

$$
\text{Experienced duration} \propto \frac{\text{novelty}}{\text{age}}
$$

For example - imagine a person is 27.
A routine year:

$$
\frac{1}{27} =  0.037
$$

A year in which they move country, learn Mandarin, start a new sport, travel frequently, etc., might have N = 1.8:

$$
\frac{1.8}{27} =  0.067
$$

| Actual age | Subjective age | Novelty factor N | Example ways to keep life distinctive |
|----|---|---|---|
| 30 | 30 | 1.00x | Work, friends, fitness, occasional travel, and trying new things |
| 35 | 32.5 | 1.08x | Pick up a new hobby, explore unfamiliar places, meet new people, or take a class |
| 40 | 35 | 1.14x | Learn a new skill seriously, travel somewhere culturally different, join a new community, or start a challenging project |
| 45 | 37.5 | 1.20x | Add a meaningful pursuit: learn a language, take up a martial art, play an instrument, volunteer, or build something |
| 50 | 40 | 1.25x | Keep learning, make new friends, take adventurous trips, change old routines, and work toward difficult goals |
| 60 | 45 | 1.33x | Keep having new experiences, learn things from scratch, stay socially active, and work on projects with clear milestones |
| 70 | 50 | 1.40x | Continue having firsts: new places, new skills, new communities, creative projects, and new challenges |
| 80 | 55 | 1.45x | Avoid excessive routine by continuing to learn, explore, build relationships, and pursue meaningful projects |
| 90 | 60 | 1.50x | Maintain roughly 50% more memory density than your age-30 baseline, not necessarily 50% more activity |
