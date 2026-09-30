---
type: object
tags:
  - algebra
  - analysis
  - course
---
# Equivalence Relation

requires:: [[Relation]] 
source:: https://en.wikipedia.org/wiki/Equivalence_relation



## Motivation

In mathematics, the idea of "equality" is incredibly important since it lets us examine the relationship between objects and study their interactions. As such, it is necessary to formalize this notion as to be able to apply it in an abstract sense. 
## Intuition

This lets us define an equivalence between objects even if they aren't _strictly_ equal. It lets us _zoom out_. 

## Definition 

*Defn* An equivalence relation $\sim$ on a set $X$ is a [[Relation|binary relation]] that is reflexive, symmetric, and transitive. That is, for all $x, y, z \in X$  we have
1) _reflexive_ ${}x \sim x{}$
2) _symmetric_ ${}y \sim x{} \iff x \sim y$  
3) _transitive_ ${}x \sim y{} \& y \sim z \implies x \sim z$ 

*Defn* The _equivalence_ class of an element $x \in X$ under $\sim$ , ${}[x]$  is taken to be 
$$
[x] = \left\{ y \in X : y\sim x\right\} 
$$


## Notation

We say a set ${}X{}$ together with a relation $\sim$ is a _setoid_, ${}(X, \sim){}$. 

