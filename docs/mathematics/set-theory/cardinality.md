---
title: Cardinality
layout: default
parent: Set Theory
nav_order: 7
---

# Cardinality

The **cardinality** of a set is the number of elements in the set.  The cardinality of a set is denoted using absolute value notation.


For example consider the set $A$ below.

$$A = \{1, 2, 3, 8, 7\}$$

We would denote the cardinality of $A$ as shown below because there are 5 elements in the set.

$$|A| = 5$$

---

## Cardinality of Infinite Sets

The cardinality of an infinite set is not a number.  In fact, we may say the cardinality of an infinite does not exist.  This is similar to a limit not converging to a number, but instead diverging to infinity.  However, we still utilize the cardinality notation for infinite sets.

Consider the set of natural numbers below.

$$\mathbb{N} = \{1, 2, 3, 4, 5, \ldots\}$$

The cardinality of the set of natural numbers is denoted as shown below.

$$|\mathbb{N}| = \infty$$

It is important that $\infty$ is not a number.  You cannot perform arithmetic operations with $\infty$ as if it were a number.  You should not perform comparison operations with $\infty$ either.  However, there are some notational conventions that implement the concept of $\infty$ as a number.  Suppose we want to indicate that set $A$ is a finite set.  We can use the notation below to indicate that the cardinality exists and so the set is not infinite (finite set).

$$|A| < \infty$$

Just to be clear, a similar notation is used to indicate that the cardinality of a set is infinite.

$$|A| = \infty$$

Sets may be complex to the point where it is not clear whether a set is finite or infinite.  In this case, we can use the notation below to indicate that the cardinality of the set is unknown.

$$|A| <= \infty$$   

Notice the above notation could mean finite or infinite.  Despite all the notational conventions that are implemented, there are a few that are not considered valid such as the one shown below. 

$$|A| > \infty \;\;\; \text{ (not valid)}$$

---

## Cardinality of the Empty Set

The cardinality of the empty set is zero because there are no elements in the empty set.  The notation below is used to indicate that the cardinality of the empty set is zero.

$$|\emptyset| = 0$$

Notice the following notation is true because the cardinality of a set containing only the empty set is one.

$$|\{\emptyset\}| = 1$$

---

## Cardinality of Subsets

There is a natural relationship between the cardinality of a set and the cardinality of its subsets.  The cardinality of a subset is always less than or equal to the cardinality of the original set. Notice the following is true.  Recall that a subset leaves open the possibility for equality between sets.  As such, the cardinalities of the two sets could be equal.  The arrow below simply means "implies". 

$$A \subset B \implies |A| \leq |B|$$

In the case where set equality is not allowed we can use the notation below.

$$A \subsetneq B \implies |A| < |B|$$
