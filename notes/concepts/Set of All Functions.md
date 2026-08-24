---
type: definition
tags: []
---
# Set of All Functions

> [!abstract] Definition
> Take $A$ and $B$  to be sets. We write $B^A$ to be the set of all functions from $A$ to $B$. Notationally,
> 
> $$
> B^A = \left\{ f : A \to B \right\} 
> $$



requires:: 
source:: [[IntroToMLYounes.pdf#page=15]]

## Intuition

$\mathbb{R}^n$ is probably the easiest to intuit here. $n$ represents the cardinality of an arbitrary set $A$, and we want to eventually define a vector space where all of $\mathbb{R}^n$ is defined. As such, we need **all** of the functions that map from $A \to \mathbb{R}$ as to not miss anything. 
## Example

Let $\mathbb{R}$ be the real numbers, and $A$ be an arbitrary set. Then the _set of real value functions_  is denoted $\mathbb{R}^A = \left\{ f : A \to \mathbb{R} \right\}$.

## Non-example

Let $f : \left\{ 0, 1 \right\} \to \mathbb{R}$ via $f(x) = \sqrt{ 2 }$. Then note that $B^A \neq A^B$, since there are only two functions in the codomain, and infinite in the domain. 
