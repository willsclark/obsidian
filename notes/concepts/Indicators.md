---
type: definition
tags: []
---
# Indicators

> [!abstract] Definition
>Let $C \subseteq A$ . We define a function
>$$
>\mathbf{1}_{C} : A \to \left\{ 0, 1 \right\}  
>$$
> where
> 
> $$
> \mathbf{1}_{C}(x) = \begin{cases} \\
>  1 & \text{if } x \in C \\ \\
> 0 & \text{else}
> \end{cases}
> $$
> 



requires:: [[Set of All Functions]]
source:: [[IntroToMLYounes.pdf#page=15]]

## Intuition

We call this an indicator since it "indicates" whether or not an element is a part of a set. This is important for counting in probability, since if we want the number of times an event occurs, we can frame it as an indicator function, and count occurences.

## Non-Example

$$
\mathbf{1}_{x \in C} = \begin{cases}
1 & \text{if } x \in C \\
-1 & \text{ else}
\end{cases}
$$
We require an indicator to be 1 or 0. Thus this is a non-example.
## Notation

- $1_{x \in C}$
