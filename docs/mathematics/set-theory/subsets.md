---
title: Subsets
layout: default
parent: Set Theory
nav_order: 3
---

# Subsets

## Definition

$A$ is a **subset** of $B$ if every element of $A$ is also an element of $B$:

$$
A \subseteq B \iff (\forall x)(x \in A \rightarrow x \in B).
$$

If $A \subseteq B$ but $A \ne B$, then $A$ is a **proper subset**:

$$
A \subset B.
$$

## Examples

Let $A=\{1,2\}$ and $B=\{1,2,3\}$.

- $A \subseteq B$ (true)
- $B \subseteq A$ (false)
- $A \subset B$ (true)

## Power set

The **power set** of $A$, written $\mathcal{P}(A)$, is the set of all subsets of $A$.

Example:

If $A=\{a,b\}$ then

$$
\mathcal{P}(A)=\{\varnothing, \{a\}, \{b\}, \{a,b\}\}.
$$

If $|A| = n$ is finite, then

$$
|\mathcal{P}(A)| = 2^n.
$$

## Useful equivalence

To prove two sets are equal, it’s common to prove:

$$
A = B \quad\text{by showing}\quad (A \subseteq B) \text{ and } (B \subseteq A).
$$
