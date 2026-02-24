---
title: Infinite Sets
layout: default
parent: Set Theory
nav_order: 4
---

# Infinite Sets

A set is **finite** if it has $n$ elements for some $n \in \mathbb{N}$.
A set is **infinite** if it is not finite.

## Countably infinite

A set $A$ is **countably infinite** (or **countable**) if there exists a bijection
$f: \mathbb{N} \to A$.

Intuition: you can “list” its elements as

$$
a_1, a_2, a_3, \dots
$$

Examples of countably infinite sets:

- $\mathbb{N} = \{0,1,2,\dots\}$
- $\mathbb{Z} = \{\dots,-2,-1,0,1,2,\dots\}$
- $\mathbb{Q}$ (rational numbers)

## Uncountable

A set $A$ is **uncountable** if no bijection $\mathbb{N} \to A$ exists.

Canonical example: the real numbers $\mathbb{R}$.

A classic result (Cantor’s diagonal argument) shows:

$$
(0,1) \subseteq \mathbb{R} \text{ is uncountable.}
$$

## “Same size” for infinite sets

For infinite sets, “same size” means there is a **bijection** between them.

Example idea:

$$
\mathbb{N} \text{ and } 2\mathbb{N}=\{0,2,4,\dots\} \text{ have the same cardinality}
$$

because $f(n)=2n$ is a bijection $\mathbb{N}\to 2\mathbb{N}$.
