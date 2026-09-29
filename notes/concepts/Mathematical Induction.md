---
type: theorem
tags: []
---
# Mathematical Induction

> [!abstract] Statement
> Let ${}P_{1}, P_{2}, \dots, P_{n}, \dots{}$ be a list of statements that may or may not be true. The principle of _mathematical induction_ says: if the statements satisfy
>  i) ${}P_{1}{}$ is true
>  ii) if ${}P_{n}{}$ is true, then ${}P_{n + 1}{}$ is true
>
>Then all the statements ${}P_{1}, P_{2}, \dots P_{n}, \dots{}$ are true


## Proof sketch

Follow's directly from [[Peano's Axioms]]. The _Axiom of Induction_

## Why is it true?

Consider the set 
$$
\mathcal{A} = \left\{ n \in \mathbb{N} \mid P_{n} \; \text{is true} \right\} 
$$

Clearly ${}A \subset \mathbb{N}{}$. ${}\mathcal A{}$ satisfies both conditions above; basis for induction, and the induction hypothesis. So ${}\mathcal A = \mathbb{N}{}$. 
