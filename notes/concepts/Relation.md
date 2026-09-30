# Relation

requires:: [[Cartesian Product]]
source::  https://en.wikipedia.org/wiki/Cartesian_product
## Motivation

We are often concerned with the relationship between elements. Formally, we ask the question, "is this thing related to this other thing?" As it turns out, defining a relation is fundamental for all of mathematics.

## Intuition

I like to think of relations as a "membership query." For example, it might be important to ask, is $a$ related to $b$? If it is, its a yes (i.e. its a member). Else, its no.
## Definition 

*Defn: (Set Theoretic)* A _binary_ relation ${}\mathcal{R}{}$ from a set $A$ to a set $B$ is a subset of the cartesian product between $A$ and $B$. Notationally,

$$
\mathcal{R} \subseteq A \times B = \left\{ (a, b) : a \in A, b \in B \right\} 
$$
When ${}A = B{}$ we say that $\mathcal{R}$ is a binary relation on $A$. 

*Defn: (n-ary relation)* An _n-ary_ relation $\mathcal{R}$ on $n$ sets ${}A_{1}, A_{2}, \dots A_{n}{}$ is a subset of the "${}n{}$ fold cartesian product," namely
$$
\mathcal{R} \subseteq A_{1} \times A_{2}\times\dots \times A_{n} = \left\{ (a_{1}, a_{2}, \dots, a_{3}) : a_{i} \in A_{i} \right\} 
$$
