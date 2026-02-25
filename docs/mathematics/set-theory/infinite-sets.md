---
title: Infinite Sets
layout: default
parent: Set Theory
nav_order: 4
---

# Infinite Sets

In order to define infinite sets, we first need to define finite sets.

A set is a finite set if it contains a finite number of elements. This means there are a limited number of elements in the set. Notice this has nothing to do with whether the elements are bounded.  The set of numbers in the interval from 0 to 1 is an infinite set even though all the elements are greater than 0 and less than 1. 

Infinite sets are sets that are not finite.  An infinite set is a set that contains an infinite number of elements.  This means there are an unlimited number of elements in the set. The set below represents an infinite set because it contains an infinite number of elements.

$$A = \{1, 2, 3, 4, 5, \ldots\}$$

Infinite sets are categorized into two types:

1. Countably infinite sets
2. Uncountably infinite sets

## Countably Infinite Sets

Consider the set of natural numbers below.  

$$\mathbb{N} = \{1, 2, 3, 4, 5, \ldots\}$$

Obviously, that set is infinite.  However, notice that we can still list the elements of the set in a sequence.  We can list the elements of the set in a sequence because there is a first element, a second element, a third element, and so on.

The set of natural numbers is an example of a countably infinite set. In fact, it is the basis for determining whether a set is countably infinite.  A set is a countably infinite set if we can establish a one-to-one correspondence between the elements of the set and the natural numbers.  Restated, a countably infinite set means the elements can be enumerated in a sequence. 

## Uncountably Infinite Sets

There are sets that are so dense that we cannot list the elements of the set in a sequence.  The set of real numbers is an example of an uncountably infinite set.   Suppose we considered all non-negative real numbers.  Obviously we would start with the number zero, but how could we meaningfully determine the next value.  Any value we pick would have infinitely many values between it and the previous value. This description is overly simplistic to the point of being abusive.  

Determining whether a set is countably infinite or uncountably infinite can be a very difficult task.


## Example of Countably Infinite Set

Consider the set of integers below.

$$\mathbb{Z} = \{\ldots, -3, -2, -1, 0, 1, 2, 3, \ldots\}$$

The set of integers is an example of a countably infinite set.  We can establish a one-to-one correspondence between the elements of the set of integers and the natural numbers.  At first this may look impossible since the natural numbers only include positive integers greater than zero. However, that is true only because you are thinking of the numbers in a particular order.  Suppose we rearranged the sets in the following way:

$$\mathbb{Z} = \{0, 1, -1, 2, -2, 3, -3, \ldots\}$$

Now image we labeled the elements of the set of integers using natural numbers as follows:

$$\mathbb{Z} = \{\underbrace{0}_{1}, \underbrace{1}_{2}, \underbrace{-1}_{3}, \underbrace{2}_{4}, \underbrace{-2}_{5}, \underbrace{3}_{6}, \underbrace{-3}_{7}, \ldots\}$$

Now we see that we can establish a one-to-one correspondence between the elements of the set of integers and the natural numbers.  

## Never Compare The Size of Infinite Sets

It is important to never compare the sizes of infinite sets. Consider the set of even numbers and the set of natural numbers shown below.

$$E = \{2, 4, 6, 8, 10, \ldots\}$$

$$\mathbb{N} = \{1, 2, 3, 4, 5, \ldots\}$$

It may seem natural to assume that the set of natural numbers is larger than the set of even numbers. Afterall, the even numbers are elements of the set of natural numbers and there are numbers in the natural numbers that are not even numbers.  However, notice that we can construct the even numbers using set-builder notation as follows:

$$E = \{2n \; | \; n \in \mathbb{N}\}$$

Notice that the iterator $n$ is iterating over the natural numbers.  Does this not imply a correspondence between the natural numbers and the even numbers?  Notice this correspondence is shown below.

$$E = \{\underbrace{2}_{1}, \underbrace{4}_{2}, \underbrace{6}_{3}, \underbrace{8}_{4}, \underbrace{10}_{5}, \ldots\}$$

Is it not the case that the set of even numbers are formed by multiplying the natural numbers by 2?

## Countable vs Uncountable Infinite Sets

As stated, we never compare the sizes of infinite sets.  However, there is an arguement to be made about the density of a set.  The set of real numbers is much more dense than the set of natural numbers.  The set of real numbers is uncountably infinite while the set of natural numbers is countably infinite.  This type of analysis is called measure theory and can be quite complex.   Measure theory is at the heart of probability theory. 

## All Finite Sets Are Countable

To be complete, it is worth noting that all finite sets are countable.  A finite set is a set that contains a finite number of elements.  Since there are only a finite number of elements in the set, we can easily establish a one-to-one correspondence between the elements of the set and the natural numbers. We simply do not need to use all the natural numbers to enumerate the elements of the finite set.


