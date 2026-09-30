source::[[205A_L1_XHANG.pdf#page=3]]
requires :: [[notes/concepts/Peano's Axioms|Peano's Axioms]] [[Arithmetic Operations on Nat]] [[Order Structure]]
# Definition

The natural number set $Nat$ is a set of elements with a successor function ${}S{}$ defined on it, satisfying [[Peano's Axioms]]. Formally,
$$
Nat = \left\{ 0, S(0), S(S(0)), \dots\right\} 
$$
Or rather, to avoid the nested function compositions, we use the numerals 0, 1, 2, 3, to represent the number of times the successor function ${}S{}$, has been applied:
$$
Nat \sim \left\{ 0, 1, 2, \dots  \right\} = \mathbb{N}
$$
## Motivation

The rigorous definition of the natural numbers, $Nat$, is given by *Peano's Axioms*, but it's important to keep in mind that *peano's* motivation was to construct the natural numbers using the _fewest_ possible axioms to generate the natural numbers _fully_. 

${}\mathbb{N}{}$ is important for the arithmetic we can perform on it.
## Insight

We define $Nat$ , the "natural number set," to be a set 
- containing $0$
- and a successor function ${}s(x): Nat \to Nat{}$ satisfying [[Peano's Axioms]]

The natural number set is tradionally thought of as a "counting set," but its crucial to remember that the numbers themselves don't make up the set, but instead, the structure defines ${}\mathbb{N}{}$. 

## Example

Take  ${} \eta \in \mathcal{A}{}$. Define ${}S : \mathcal{A} \to \mathcal{A}{}$ via $x \to x*$. This gives us the set

$$
Nat = \left\{ \eta, \eta*, \eta**, \eta ***, \dots \right\} 
$$

Which, if we denote $$0 = \eta, 1 = \eta*, 2 = \eta **, \dots$$
we recover
$$
Nat = \left\{ 0, 1, 2, 3, \dots \right\} 
$$

# Arithmetic Operations 

$Nat$ has addition $+$ and multiplication $\cdot$ defined using only $\mathbf{0}$ and $\mathbf{s(x)}$, and satisfying commutativity and distributivity.


# Order Structure 

