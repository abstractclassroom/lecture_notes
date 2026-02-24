---
title: Definition
layout: default
parent: Set Theory
nav_order: 1
---

# Definition

A **set** is a collection of *distinct* objects called **elements**.

## Membership

- $x \in A$ means “$x$ is an element of $A$.”
- $x \notin A$ means “$x$ is not an element of $A$.”

Example:

Let $A = \{2,4,6\}$. Then $4 \in A$ but $5 \notin A$.

## Equality of sets

Two sets are equal when they contain exactly the same elements:

$$
A = B \iff (\forall x)(x \in A \leftrightarrow x \in B).
$$

So order and repetition do not matter:

$$
\{1,2,2,3\} = \{3,2,1\} = \{1,2,3\}.
$$

## Common sets

- Empty set: $\varnothing$ (or $\{\}$)
- Universal set (context-dependent): $U$

When we talk about complements, we must specify a universe $U$.
