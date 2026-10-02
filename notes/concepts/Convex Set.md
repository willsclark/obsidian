---
type: object
tags: []
---
# Convex Set

requires:: [[Line Segment]]
source:: [[L01_Optimization.pdf]][[IntroToOptimization.pdf#page=61]]


## Intuition

Take two points on a graph. Connect them. If the graph is below the line segment, the function is convex. 

![[convex_sets.png]]

## Definition 

*Defn:* A set ${}S \subseteq \mathbb{R}^n{}$ is _convex_ if for all ${}\mathbf{u}, \mathbf{v} \in \mathbb{R}^n{}$, the line segment between ${}\mathbf{u} \; \text{and} \; \mathbf{v}{}$, ${}l_{uv} \in S{}$. 

## Examples

- ${}[-2, 2], \; (0, 1), \; [0, \infty), \; \mathbb{R}{}$

A set with a gap is **not convex**

![[convex_nonconvex.png]]