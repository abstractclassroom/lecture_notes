---
title: Cardinality
layout: default
parent: Set Theory
nav_order: 5
---

# Cardinality

## Finite cardinality

If $A$ is finite, then $|A|$ is the number of elements in $A$.

Example:

$$
A = \{a,b,c\} \implies |A| = 3.
$$

## Infinite “cardinality” is different

For infinite sets, you **cannot** measure size by counting to a last element.
Instead, we compare sizes using **bijections**:

Two sets $A$ and $B$ have the same cardinality if there exists a bijection $f: A \to B$.

We write:

$$
|A| = |B| \quad \text{(meaning: there is a bijection)}.
$$

This is why many people informally say “$|A|$ doesn’t exist the usual way for infinite sets.”
The modern definition *does* assign infinite cardinalities, but it is based on bijections.

## Comparing sizes

- $|A| \le |B|$ means there exists an injective function $A \to B$.
- $|A| < |B|$ means $|A| \le |B|$ but $|A| \ne |B|$.

## Standard infinite cardinalities

- Countable infinity:

$$
|\mathbb{N}| = \aleph_0
$$

- Continuum (size of the reals):

$$
|\mathbb{R}| = \mathfrak{c}
$$

and Cantor showed:

$$
\aleph_0 < \mathfrak{c}.
$$
