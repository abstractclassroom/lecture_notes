---
title: Set Operations
layout: default
parent: Set Theory
nav_order: 5
---

# Set Operations

There are many operations that can be performed on sets.  Below are some of the most common set operations.

* **Union**: The union of two sets $A$ and $B$ is the set of all elements that are in $A$ or in $B$.  The union of $A$ and $B$ is denoted by $A \cup B$.
* **Intersection**: The intersection of two sets $A$ and $B$ is the set of all elements that are in both $A$ and $B$.  The intersection of $A$ and $B$ is denoted by $A \cap B$.
* **Difference**: The difference of two sets $A$ and $B$ is the set of all elements that are in $A$ but not in $B$.  The difference of $A$ and $B$ is denoted by $A \setminus B$.
* **Symmetric Difference**: The symmetric difference of two sets $A$ and $B$ is the set of all elements that are in $A$ or in $B$ but not in both.  The symmetric difference of $A$ and $B$ is denoted by $A \triangle B$.
---

## Set Builder Notation

Below are the set builder notations for the above set operations.  The symbol $\lor$ is used to denote "or" and the symbol $\land$ is used to denote "and".  The symbol $\lnot$ is used to denote "not".  The symbol $\in$ is used to denote "is an element of".  The symbol $\not \in$ is used to denote "is not an element of".

$$
\begin{align*}
A \cup B & = \{x : x \in A \lor x \in B\} \\
A \cap B & = \{x : x \in A \land x \in B\} \\
A \setminus B & = \{x : x \in A \land x \not \in B\} \\
A \triangle B & = \{x : (x \in A \land x \not \in B) \lor (x \not \in A \land x \in B)\}
\end{align*}
$$

---

### Union Example 

Consider the two sets $A$ and $B$ below.

$$
\begin{align*}
A & = \{1, 2, 3\} \\
B & = \{3, 4, 5\}
\end{align*}
$$

The union of $A$ and $B$ is the set of all elements that are in $A$ or in $B$.  The union of $A$ and $B$ is denoted by $A \cup B$.  Remember, order does not matter and sets do not contain duplicates.  As a result, the union of $A$ and $B$ is shown below.

$$
A \cup B = \{1, 2, 3, 4,5\}
$$


---

### Intersection Example

Consider the two sets $A$ and $B$ below.

$$
\begin{align*}
A & = \{1, 2, 3\} \\
B & = \{3, 4, 5\}
\end{align*}
$$

The intersection of $A$ and $B$ is the set of all elements that are in both $A$ and $B$.  The intersection of $A$ and $B$ is denoted by $A \cap B$.   The intersection of $A$ and $B$ is shown below.

$$A \cap B = \{3\}$$


---

### Difference Example

Consider the two sets $A$ and $B$ below.

$$
\begin{align*}
A & = \{1, 2, 3\} \\
B & = \{3, 4, 5\}
\end{align*}
$$

The difference of $A$ and $B$ is the set of all elements that are in $A$ but not in $B$.  The difference of $A$ and $B$ is denoted by $A \setminus B$.  The difference of $A$ and $B$ is shown below.

$$
A \setminus B = \{1, 2\}
$$


---

### Symmetric Difference Example

Consider the two sets $A$ and $B$ below.

$$
\begin{align*}
A & = \{1, 2, 3\} \\
B & = \{3, 4, 5\}
\end{align*}    
$$

The symmetric difference of $A$ and $B$ is the set of all elements that are in $A$ or in $B$ but not in both.  The symmetric difference of $A$ and $B$ is denoted by $A \triangle B$.  The symmetric difference of $A$ and $B$ is shown below.

$$
A \triangle B = \{1, 2, 4, 5\}
$$

---

## Disjoint Sets

Two sets are disjoint if they have no elements in common.  The sets $A$ and $B$ are disjoint if their intersection is the empty set.  For example, the sets below are disjoint because they have no elements in common.

$$
\begin{align*}
A & = \{1, 2, 3\} \\
B & = \{4, 5, 6\} \\
A &\cap B  = \emptyset \;\;\text{(disjoint sets)}
\end{align*}
$$

## Partitions of a Set

A partition of a set is a collection of non-empty, disjoint subsets of the set that together contain all the elements of the set.  For example, consider the set $A$ below.

$$
A = \{1, 2, 3, 4, 5, 6\}
$$

A partition of the set $A$ is shown below.  Notice that the subsets are non-empty, disjoint, and together contain all the elements of $A$.

$$
\begin{align*}
P_1 & = \{1, 2\} \\
P_2 & = \{3, 4\} \\
P_3 & = \{5, 6\} \\
P & = \{P_1, P_2, P_3\} \;\;\; P \text{ is a partition of } A
\end{align*}
$$

Notice that the partitions are subsets.  All pairwise intersections of the subsets are empty.  The union of the subsets is the original set $A$.

$$
\begin{align*}
P_1 \cap P_2 & = \emptyset \\
P_1 \cap P_3 & = \emptyset \\
P_2 \cap P_3 & = \emptyset \\
P_1 \cup P_2 \cup P_3 & = A
\end{align*}    
$$

