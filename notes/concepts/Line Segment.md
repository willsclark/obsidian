---
type: object
tags: []
---

# Line Segment

requires:: 
source:: [[IntroToOptimization.pdf#page=59]] 

## Intuition

This is the set of real-valued numbers between two points. It's literally the line connecting them. 

![[lineSegment.png]]
## Definition 


*Defn:* The _line segment (convex combination)_  ${}l{}$, between two points ${}\vec{x}{}$ and ${}\vec{y}{}$ in ${}\mathbb{R}^n{}$ is the set of points on the straight line joining them. 

- If ${}\mathbf{z} \in {l_{xy}}$, we have $$
  y - z = \alpha (x - y), \qquad \alpha \in [0, 1]_{\mathbb{R}}
  $$
Hence, we can define the line segment precisely as

$${}l = \left\{ \alpha \mathbf{x} + (1 - \alpha) \mathbf{y} : \alpha \in [0, 1]_{\mathbb{R}} \right\}{}$$

## Alternative Names

- Chord