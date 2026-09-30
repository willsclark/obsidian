---
type: object
tags: []
---
# Order Structure

requires:: 
source:: [[205A_L2_Clark.pdf#page=1]]


## Motivation

To be able to compare elements, and have that operation be well defined. 
## Intuition

Just think of "normal" arithmetic. 1 < 2, 2 > 0, etc. 
## Definition 

*Defn* Let ${}\mathcal F{}$ be a set. An _order_ on ${}\mathcal{F}{}$ is a [[Relation|relation]] satisfying
	**O1:** _trichotomy_ For any ${}a, b \in \mathcal{F}{}$ _one_ of the following holds
	$$
	a < b, \qquad a = b, \qquad a > b
	$$
	 **O2** _transition_  For any ${}a, b, c \in \mathcal F{}$, 
	 $$
	 a < b \; \& \; b < c \implies a < c
	 $$ 
_Generally_, a set with an order ${}<{}$ is called an "ordered set"
