---
type: definition
tags:
  - analysis
---
requires:: [[Natural Number Set]]
source:: [[205A_L1_Xhang.pdf]] 
# Definitions

*Defn* The *successor function* $S : Nat \to Nat$ is a function that has $Nat$ as its domain. _Intuitively, think of $S(x)$ as $x + 1$. 


# Peano's Axioms

Now we describe the set $Nat$ using the following five axioms:
1) ${}0 \in Nat{}$
2) if ${}x \in Nat{}$, then its successor ${}S(x) \in Nat{}$ 
3) $0$ is not the successor of any element in $Nat$
4) if ${}x, y \in Nat{}$  have the same successor, that ${}x = y{}$. 
5) *Axiom of Induction* if ${}A{}$ is any subset of $Nat$ such that 
	1) ${}0 \in A{}$
	2) if ${}x \in A{}$, then ${}S(x) \in A{}$
	then $A = Nat$ . 


## Intuition

We want the fewest amount of axioms, _rules_, to completely describe the natural numbers. The major discovery is that we only need two things: 
- The existence of at least one natural number
- A well defined function, called the successor function


