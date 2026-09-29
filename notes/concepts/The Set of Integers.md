---
type: object
tags: []
---
# The Set of Integers

requires:: [[Natural Number Set]], [[Equivalence Relation]]
source:: [[205A_L2_XHANG.pdf#page=1]]

## Motivation

Let's assume the set ${}\mathbb{N}{}$ is defined normally, with all the usual properties and structures. (${}\mathbb{N}, + , \cdot )$ is a very very well behaved structure, but it falls a bit short. 

Let's first define subtraction, "${}-{}$" as the opposite of addition. By definition, 
for ${}a, b \in \mathbb{N} {}$, the number $a - b$ is the solution to the equation 
$$
x + b = a
$$
Consider the situation where ${}a = 1, b= 2{}$ . The difference ${}1 - 2{}$ is not a natural number, and in fact, is the motivation behind constructing the integers.

## Idea

An integer should be a solution to ${}x + b = a{}$. Said differently, _each such equation  is determined by an ordered pair_ ${}(a, b){}$. 

However, there's an issue here. **Different equations may have the same solution**. 

Take, for example, ${}x + 1 = 2{}$ and ${}x + 2 = 3{}$. In either case, ${}x =1{}$ is the solution. 

Thus, an **integer** should be a **set** of these equations, or rather **a set of ordered pairs** . 

## Definition / characterizations

**Definition 1** Consider the set ${}\mathbb{N} \times \mathbb{N}{}$ of ordered pairs of natural numbers. Consider the **relation** on the set defined by
$$
(m, n) \sim (p, q) \iff m + q = n + p
$$

### The set of Integers

We define the set of integers as 
$$
\mathbb{Z} = \mathbb{N} \times \mathbb{N} / \sim 
$$
An integer is an equivalence class ${}[(m, n)]{}$, representing the difference ${}m - n{}$. 
## Properties

We identify an integer ${}n \in \mathbb{N}{}$ with the equivalence class ${}[(n, 0)]{}$, as ${} n{}$ is the solution of the equation ${}x + 0 = n{}$ . This identification allows us to consider_ ${}\mathbb{N}{}$_as a subset of ${}\mathbb{Z}{}$_
## Canonical examples
- 

## Where it shows up
- 

