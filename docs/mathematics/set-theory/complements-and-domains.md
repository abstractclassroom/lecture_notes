---
title: Complements and Domains
layout: default
parent: Set Theory
nav_order: 8
---

# Complements and Domains

The **complement** of a set $A$ is the set of all elements that are not in $A$.  The complement of $A$ is denoted by $A^c$.  Some textbooks and journals use other notation such as $\overline{A}$ or $A'$.  For this set of notes, we will use the notation $A^c$ to denote the complement of $A$.

For example, consider the set $A$ below.

$$A = \{1, 2, 3\}$$

The complement of $A$ is the set of all elements that are not in $A$.  As a result the following could be true depending on the context.

$$
\begin{align*}
4 \in A^c \\
5 \in A^c \\
6 \in A^c \\
\vdots
\end{align*}
$$  

This perhaps seems very straight forward.  However, we never really defined a universal set, also known as a domain.  Notice the following could be argued to be true.

$$
\begin{align*}
-1 \in A^c \\
\text{cat} \in A^c \\
\text{dog} \in A^c \\
\vdots \\
\text{Andromeda Galaxy} \in A^c \\
\end{align*}
$$

Notice how riddiculous the above statements appear.  In order to consider the complement of a set, a domain or universal set must be defined. 

---

## Establishing a Domain

Once a domain is established, nothing outside of the domain is considered to be in scope.  For example, let $D$ be the domain and $A$ be a set such that $A \subset D$.  The complement of $A$ is no longer so riddiculous because we are only considering elements in the domain $D$.

$$
\begin{align*}
D = \{1, 2, 3, 4, 5, 6\} \\
A = \{1, 2, 3\} \\
A^c = \{4, 5, 6\}
\end{align*}
$$

---

## Properties of Complements 

Let $A$ be a set and $D$ be the domain.  The following properties of complements hold.

$$
\begin{align*}
A \cup A^c = D \\
A \cap A^c = \emptyset \\
(A^c)^c = A \\
\end{align*}
$$

---

## De Morgan's Laws

Let $A$ and $B$ be sets and $D$ be the domain.  The following properties of complements hold.

$$
\begin{align*}
(A \cup B)^c = A^c \cap B^c \\
(A \cap B)^c = A^c \cup B^c \\
\end{align*}
$$


## Barber Paradox

Bertrand Russell's Barber Paradox is a famous paradox in set theory.  It is related to the concept of complements and domains.  The paradox is as follows:

> In a town, there is a barber who shaves all and only those who do not shave themselves.  The question is: Does the barber shave himself?

Notice the paradox
- If the barber shaves himself, then he does not shave himself (because he only shaves those who do not shave themselves).
- If the barber does not shave himself, then he shaves himself (because he shaves all those who do not shave themselves).

What is being assumed?  The barber is assumed to be an element of the domain of all people in the town.  If the barber is not part of the domain, then the rule does not apply to the barber and so there is no paradox.  

Anytime a set is constructed, it is important that the domain be well-defined.

The Barber Paradox was actually pitched by Bertrand Russell as a way to demonstrate the problems with naive set theory. His motivation is much deeper than just complements and domains.  Bertrand Russell was to provide context to self-referencing sets and the problems that arise from them. That is out of scope for this lecture.  However, removing the barber from the domain does resolve the paradox. 

