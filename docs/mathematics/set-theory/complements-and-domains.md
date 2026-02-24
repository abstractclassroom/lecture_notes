---
title: Complements and Domains
layout: default
parent: Set Theory
nav_order: 6
---

# Complements and Domains

## Universe / domain matters

A complement only makes sense relative to a **universe** $U$.

If $A \subseteq U$, the (relative) **complement** of $A$ in $U$ is:

$$
A^c = U \setminus A = \{x \in U : x \notin A\}.
$$

Example:

Let $U=\{1,2,3,4,5\}$ and $A=\{2,4\}$.

Then:

$$
A^c = \{1,3,5\}.
$$

If you change $U$, the complement changes.

## Barber paradox (why definitions need domains)

Informal statement:

> In a town, the barber shaves exactly those people who do **not** shave themselves.
> Does the barber shave himself?

Let $U$ be the set of people in the town. Define:

- $S(x)$ = “$x$ shaves himself”
- $B$ = the barber

The barber rule says:

$$
(\forall x \in U)\, (\text{barber shaves } x) \leftrightarrow \neg S(x).
$$

Now ask whether the barber shaves himself. If the barber shaves himself, then by the rule he does **not** shave himself.
If he does not shave himself, then by the rule he **does** shave himself. Contradiction.

### Lesson

Definitions that quantify over “all objects” can be inconsistent if the **domain** is not well-defined or if the rule creates self-reference.
Being explicit about domains (universes) prevents many paradoxes.
