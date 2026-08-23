# Power Set

> [!abstract] Definition
> Let $A$ be a set. Then $\mathcal{P}(A)$ denotes the "power set of $A$,"
> where 
> $$
> P(A) = \{B \mid B \subseteq A\} 
> $$
> the set of all subsets of $A$.

requires:: 
source:: [[IntroToMLYounes.pdf#page=15]] https://en.wikipedia.org/wiki/Power_set


## Properties

$$
|\mathcal{P}(A)| = 2^{|A|}
$$
## Intuition

The power set gets its name since the number of elements in the power set is equal to 2 raised to the number of elements in the original set. 

## Example

Take $A = \{x, y\}$, then $\mathcal{P}(A) = \{\{x, y\}, \{x\}, \{y\}, \{\emptyset\}\}$. Indeed, $|\mathcal{P}(A)| = 2^2 = 2^{|A|}$.

## Non-example

Take $B = \{1\}$. Then $\mathcal{P}(B) = \{1\}$ is **not** the power set, since it does not contain the empty set. 
## Notation

$$
\mathcal{P}(A), \; 2^S, \; \mathbb{P}(A)
$$

