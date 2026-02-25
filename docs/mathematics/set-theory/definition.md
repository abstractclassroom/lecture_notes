---
title: Definition
layout: default
parent: Set Theory
nav_order: 1
---

# Definition

A **set** is a collection of *distinct* objects called **elements**.

---

## Properties Of Sets

All mathematical sets have the following properties:

- **Unordered**: The order of elements does not matter. $$\{1,2\} = \{2,1\}$$

- **Distinct**: Each element can only appear once. 
$$\{1,2,2,3\} = \{1,2,3\}$$

The notion of distinct is an important concept in mathematics.  If an object is distinct then it is different from all other objects.  However, this definition relies on the meaning of equivalence which can be overloaded and redefined for certain contexts. For example, pizzas ordered from different restaurants will taste differently.  If equivalence is defined as having the same taste, then two pizzas that do not taste the same are not equivalent and so both pizzas are distinct. However, if equivalence is defined as just being a pizza, then two pizzas having different toppings may then be considered equivalent and so not distinct. 

In general, sets do not contain order and they do not contain duplicates.  Adding an element to a set that already contains that element does not change the set.  Mathematically, `idempotent` actions (or operations) are operations that are inert if applied more than once.  Once an element has been added to a set, adding it again does not change the set and so the operation of adding an element to a set is idempotent. 

---

### Sets vs. Lists

A **list** is an ordered collection of objects that may contain duplicates. For example, the list $$[1,2,2,3]$$ is not the same as the list shown below $$[3,2,1]$$ because the order of elements matters in a list.  In contrast, the set $$\{1,2,2,3\}$$ is the same as the set $$\{3,2,1\}$$ because the order of elements does not matter in a set and duplicates are not allowed (ignored).  

Sets are almost always defined using curly braces.  Lists are almost always defined using square brackets.  Tuples are similar to lists and are almost always defined using parenthesis.

* Set Example :  $$\{1,2,3\} = \{3,2,1\}$$
* List Example : $$[1,2,3] \neq [1,3,2]$$
* Tuple Example : $$(1,2,3) \neq (2,3,1)$$

---

## Membership


It is important to distinguish between a set and its elements.  The symbol $$\in$$ 
is used to denote membership.  The symbol 
$$\notin$$ is used to denote non-membership.  If $A$ is a set and $x$ is an object, then:

- $$x \in A$$ means “$$x$$ is an element of $$A$$.”
- $$x \notin A$$ means “$$x$$ is not an element of $$A$$.”

Example:

Let $$A = \{2,4,6\}$$. Then $$4 \in A$$ but $$5 \notin A$$.

---

## Equality of sets

Two sets are equal when they contain exactly the same elements.  Remember, order does not matter.


Example:
Let $$A = \{1,2,3\}$$ and $$B = \{3,2,1\}$$. Then $$A = B$$ because they contain the same elements.  However, if $$C = \{1,2\}$$, then $$A \neq C$$ because $$C$$ does not contain the element $$3$$ which is in $$A$$.


