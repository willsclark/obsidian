---
type: object
tags: []
---
# Optimization

requires:: 
source:: [[L01_Optimization.pdf]]

## Motivation

- CS / ML: 
	- Can fit a predictor by minimizing prediction error
	- Neural-nets minimize a loss function
- Econ
	- Choose a price to maximize revenue
## Definition 

*Defn:* Let ${}f{}$ be a function on ${}S \subseteq \mathbb{R}{}$. Take ${}x \in S{}$. We want
$$
\min_{x \in A} f(x)
$$
- If ${}S = \mathbb{R}{}$ we say that the optimization is *unconstrained*. 
- If ${}S \subset \mathbb{R}$ we say that the optimization is *constrained.*

### Terminology
 - ${}x{}$ is called the "Decision Variable"
 - ${}f{}$ is called an "Objective function" 
 - ${}S{}$ is the "Feasible Set"

## Lemonade Example

*Q*: A manager wants to determine the optimal price, ${}p{}$, for lemonade. Let 
${}D = 10 - p{}$ be the demand, where ${}p \in [0, 10]_{\mathbb{R}}{}$. The revenue function is thus 
$$
R : [0, 10]_{\mathbb{R}} \to \mathbb{R} \qquad \text{via} \qquad p \mapsto p (10 - p)
$$
Notice ${}p(10 - p) = 10p - p^2{}$ . Since we are interesting in _maximizing_ ${}p{}$, we can multiply ${}\mathbb{R}{}$ by ${}-1{}$ and minimize. Hence, 
$$
-R(p) = p^2 - 10p = (p -5)^2 + 25
$$
Where ${}-R{}$ achieves a minimum at ${}p = 5{}$. So ${}p = 5{}$ is the maximizing value. 

