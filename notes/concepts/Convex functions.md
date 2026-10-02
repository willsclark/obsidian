---
type: object
tags: []
---

# Convex functions

requires:: [[Convex Set]]
source:: [[L01_Optimization.pdf]] 
## Motivation

## Intuition

## Definition 

*Defn:* Let ${}f : \mathbb{R} \to \mathbb{R}{}$ on a [[Convex Set |convex set]] ${}S{}$. The function is _convex_ if for all ${}x, y \in S{}$ and ${}t \in [0, 1]_{\mathbb{R}}{}$ 
$$
f((1 - t)x + ty) \leq (1 - t)f(x) + tf(y)
$$

