---
title: Famous infinite sets
layout: default
parent: Set Theory
nav_order: 10
---

# Famous Infnite Sets

Some sets in mathematics are so common and important they have their own special notation.

---
## Natural numbers
The set of natural numbers is denoted by $\mathbb{N}$ and is defined as
$$\mathbb{N} = \{1, 2, 3, 4, 5, \ldots\}$$

---

## Whole Numbers

The set of whole numbers is not universally defined.  It is not common for mathematicians to reference the whole numbers.  Many define the whole numbers as the set of natural numbers plus zero.  In any case, the set of whole numbers is denoted by $\mathbb{W}$ and is defined as
$$\mathbb{W} = \{0, 1, 2, 3, 4, 5, \ldots\}$$

As mentioned, the whole numbers may be defined using the natural numbers as shown below.
$$\mathbb{W} = \mathbb{N} \cup \{0\}$$

Notice the zero had to be added as a union.  Unions are only defined for sets.  Zero as a number is not a set, so a singleton set was created to include zero in the union.

---

## Integers
The set of integers is denoted by $\mathbb{Z}$ and is defined as
$$\mathbb{Z} = \{\ldots, -3, -2, -1, 0, 1, 2, 3, \ldots\}$$

The symbol $\mathbb{Z}$ may seem strange given the symbols $\mathbb{N}$ and $\mathbb{W}$, but it is derived from the German word "Zahlen" which means "numbers".  The set of integers includes all the natural numbers, whole numbers, and their negative counterparts.

---

## Rational Numbers

The set of rational numbers is denoted by $\mathbb{Q}$ and is defined as
$$\mathbb{Q} = \left\{\frac{a}{b} : a \in \mathbb{Z}, b \in \mathbb{Z}, b \neq 0\right\}$$

The set of rational numbers includes all the fractions of two integers where the denominator is not zero.

Notice that $\mathbb{Z} \subset \mathbb{Q}$.  Why is this the case?  Consider the number $5 \in \mathbb{Z}$. Notice the number $5$ can be expressed as a fraction of two integers as shown below.
$$5 = \frac{5}{1}$$

Since $5,1 \in \mathbb{Z}$ and $1 \neq 0$, then $5 \in \mathbb{Q}$.  Every integer can be expressed as a fraction of two integers, so every integer is a rational number.  However, not every rational number is an integer.  For example, the rational number $\frac{1}{2}$ cannot be expressed as an integer.

---

## Irrational Numbers

The set of irrational numbers is denoted as $\mathbb{Q}^c$.  Recall that the notation $A^c$ is used to denote the complement of a set $A$.  The irrationals would be difficult to define directly.  Fortunately, we do not have to define the irrationals directly because they are the set of numbers that are not rational.  This implies the set of irrational numbers is the complement of the set of rational numbers.  

$$\mathbb{Q}^c = \{x : x \not \in \mathbb{Q}\}$$

The set of irrational numbers includes all the numbers that cannot be expressed as a fraction of two integers.  For example, the number $\pi$ is an irrational number because it cannot be expressed as a fraction of two integers.  The number $e$ is also an irrational number for the same reason.  There are numbers where it is not known whether they are rational or irrational.  

---

## Real Numbers

While defining the set of irrational numbers, notation was clumsily used and a complement was implied without defining a domain.  The set of real numbers is effectively the implied domain.

$$\mathbb{R} = \mathbb{Q} \cup \mathbb{Q}^c$$

All real numbers are either rational or irrational.  The set of real numbers includes all the rational numbers and all the irrational numbers.

---

## Complex Numbers

The set of complex numbers is denoted by $\mathbb{C}$ and is defined as
$$\mathbb{C} = \{a + bi : a \in \mathbb{R}, b \in \mathbb{R}, i^2 = -1\}$$

The set of complex numbers includes all the numbers that can be expressed in the form $a + bi$ where $a$ and $b$ are real numbers and $i$ is the imaginary unit.  The imaginary unit is defined as a number such that when it is squared, it equals negative one.  The set of complex numbers includes all the real numbers because we can express any real number as a complex number by setting $b = 0$.  For example, the real number $5$ can be expressed as a complex number as shown below.
$$5 = 5 + 0i$$


Complex numbers were discovered many centuries ago.  The story surrounding the discovery of complex numbers is quite interesting.  The discovery of complex numbers was not a single event, but rather a gradual process that took place over several centuries.  The concept of complex numbers was first introduced in the 16th century by Italian mathematician Gerolamo Cardano while he was trying to solve cubic equations.  However, it was not until the 18th century that complex numbers were fully developed and understood by mathematicians such as Leonhard Euler and Carl Friedrich Gauss.  Today, complex numbers are an essential part of mathematics and have applications in various fields such as physics, engineering, and computer science.

Prior to the formal development of complex numbers, equations like the one shown below were considered unsolvable because they had no real solutions.
$$x^2 + 1 = 0$$

Afterall, if the domain is simply $\mathbb{R}$, then the above equation makes no sense.  Squaring any real number will always yield a value greater than or equal to zero. Then adding one to that value will always yield a value greater than or equal to one. So how could the result be zero? The solution set was empty.  However, with the introduction of complex numbers, we can now solve the equation as shown below.
$$x^2 + 1 = 0$$
$$x^2 = -1$$
$$x = \pm i $$

---

## Chain of Subsets

Below provides some insight into the relationships between the famous infinite sets.  Notice the chain of subsets below.
$$\mathbb{N} \subset \mathbb{W} \subset \mathbb{Z} \subset \mathbb{Q} \subset \mathbb{R} \subset \mathbb{C}$$

Notice the irrational numbers are not included in the chain above.  The chain below includes the irrational numbers.
$$\mathbb{Q}^c \subset \mathbb{R} \subset \mathbb{C}$$

