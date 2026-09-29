---
type: definition
tags: []
---
# Arithmetic Operations on Nat

### Addition

We define *addition* "${}+{}$" as the following:
1) For any $a \in \mathbb{N}$,  we have $$ a + 0 := a$$
2) For any $a, b \in \mathbb{N}$ we recursively define 
$$ a + S(b) := S(a + b)$$
### Multiplication

We define *multiplication* "$\cdot$" as the following
1) For any $a \in \mathbb{N}$, we have 
   $$
   a \cdot 0 := 0
   $$
2) For $a, b \in \mathbb{N}$ we recursively define 
   $$
   a \cdot S(b) := a + (a \cdot b)
   $$

requires:: [[Natural Number Set]]
source:: [[205A_L1_Xhang.pdf]]

## Intuition

The natural number set is not important for its set-theoretic properties, but rather the "naturalness" of the operations we can perform on it. Indeed, we can define addition as repeatedly applying the successor function to a certain element. Similarly, we take multiplication to be repeatedly applying addition


## Subtraction Cannot Always Be Performed

In some cases, subtraction is well defined. ${}4 - 2 = 2 \in \mathbb{N} {}$, but ${}1 - 2 \notin \mathbb{N}{}$. And in fact, this begs the question, **How do we enlarge ${}\mathbb{N}{}$?





