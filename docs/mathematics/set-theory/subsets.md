---
title: Subsets
layout: default
parent: Set Theory
nav_order: 3
---

# Subsets

$A$ is a **subset** of $B$ if every element of $A$ is also an element of $B$. The notation below is used to indicate that $A$ is a subset of $B$.

$$A \subset B$$

In mathematics, when we want to negate a statement, we typically use a slash through a symbol. If we want to indicate that $A$ is not a subset of $B$, we use the notation below.

$$A \not \subset B$$

The subset notation somewhat follows the convention of the less than or greater than symbols. The two expressions below are equivalent and indicate that $A$ is a subset of $B$.  The second expression indicates that $B$ is a **superset** of $A$.

Even though the expressions are equivalent, the subset notation is more commonly used than the superset notation.

## Subset vs. Proper Subset

Suppose we consider the statement below are realize it is a true statement.

$$A \subset A$$

This statement is trivially true because every element of $A$ is also an element of $A$. You will occasionally see the notation below to explicitly remind the reader that $A$ is a subset of $B$ and that $A$ and $B$ could be the same set.

$$A \subseteq B$$

However, this is purely redundant and boils down to a stylistic choice.  The notation $\subset$ is more commonly used to indicate that $A$ is a subset of $B$ and that $A$ and $B$ could be the same set.

However, there are times when  we want to indicate that $A$ is a subset of $B$ but $A$ and $B$ are not the same set.  In this case, we use the notation below to indicate that $A$ is a **proper subset** of $B$.

$$A \subsetneq B$$


## Equality of Sets

There are times when we want to prove that two sets are in fact equivalent. Determining whether two large sets filled with complex objects can be very difficult.  A mathematician may try to establish that $A$ and $B$ are equal by showing that $A$ is a subset of $B$ and that $B$ is a subset of $A$.  If both statements are true, then we can conclude that $A$ and $B$ are equal sets.  The notation below is used to indicate that $A$ and $B$ are equal sets.

If the two statements below are true, then we can conclude that $A$ and $B$ are equal sets.
$$A \subset B$$
$$B \subset A$$ 

When two sets are equal, we can use the notation below to indicate that $A$ and $B$ are equal sets.
$$A = B$$

## Subset Example

Suppose we have the following sets.
$$A = \{1, 2, 3\}$$
$$B = \{1, 2, 3, 4\}$$

Since every element of $A$ is also an element of $B$, we can conclude that $A$ is a subset of $B$.
$$A \subset B$$

However, notice that $B$ is not a subset of $A$ because there is an element of $B$ that is not an element of $A$.
$$B \not \subset A$$

## Equality of Sets Example

Suppose we have the following sets.
$$A = \{1, 2, 3\}$$
$$B = \{3, 2, 1\}$$

Since every element of $A$ is also an element of $B$, we can conclude that $A$ is a subset of $B$.
$$A \subset B$$

Since every element of $B$ is also an element of $A$, we can conclude that $B$ is a subset of $A$.
$$B \subset A$$

Since $A$ is a subset of $B$ and $B$ is a subset of $A$, we can conclude that $A$ and $B$ are equal sets.
$$A = B$$

## Notation Caveat

Consider the following sets.
$$A = \{1, 2, 3\}$$
$$B = \{1, 2, 3, 4\}$$

It is not appropriate to use the notation below.

$$A \in B$$

The notation above indicates that $A$ is an element of $B$.  However, $A$ is not an element of $B$.  The elements of $B$ are the numbers 1, 2, 3, and 4.  The set $A$ is not an element of $B$.  The set $A$ is a subset of $B$, but it is not an element of $B$.  The notation below is appropriate to indicate that $A$ is a subset of $B$.

### Sets In Sets

Suppose we have the following sets.
$$A = \{1, 2, 3\}$$
$$B = \{1, 2, 3, 4\}$$
$$C = \{A, B\}$$

The following statements are valid statements and true.
$$A \in C$$
$$B \in C$$
$$A \subset B$$
$$B \not \subset A$$
$$1 \in A$$

**The following statements are not valid and represent a misuse of notation.**
$$A \in B \;\;\;\;\text{wrong notation}$$
$$B \in A \;\;\;\;\text{wrong notation}$$
$$A \subset C \;\;\;\;\text{wrong notation}$$
$$1 \in C \;\;\;\;\text{wrong notation}$$





