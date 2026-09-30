---
type: object
tags:
  - algebra
  - analysis
---
# Function

requires:: [[Relation]]
source:: https://en.wikipedia.org/wiki/Function_(mathematics)
## Motivation

## Intuition

## Definition 

*Defn:* A _function_ with domain $X$ and codomain $Y$ is a binary [[relation]] between $X$ and $Y$ that satisfies the following two conditions
1) For every $x \in X$, theres $y \in Y$ such that ${}(x,y) \in \mathcal{R} \iff x \mathcal{R}y{}$
2) If ${}(x, y) \in \mathcal{R}{}$ and ${}(x, z) \in \mathcal R {}$, then ${}y = z{}$. 
### Example
![[Function.png|423]]

This is a function. Every value in $X$ is the first element in only one ordered pair. 
${}(1, D), (2, C), (3, C){}$. Intuitively, this means that the function maps every input to the _same_ output. The set $Y$ above is not ${}\mathrm{Im} f{} = \left\{ D, C \right\}$. 

### Non Example
![[NonFunction.png|435]]




[^1]: 

This is not a function. Every element in the domain ${}X{}$ is not mapped to a value. Indeed, ${}(2, B), (2, C){}$ has $2$ as the first element, which violates part 2 of the definition. 