---
title: Representations
layout: default
parent: Set Theory
nav_order: 2
---

# Representations

There are three common ways to represent sets.

1. Sentence form
2. Roster notation
3. Set-builder notation

Some of these are more concise than others and may require more mathematical maturity.  We will cover the basics for all three.

## Sentence form

This is the most straightforward way to describve a set.  A mathematician may verbally say something like "The set of numbers 1 through 10".  This seems very straightforward.  However, sentence form tends to be less precise.  When precision is implemented in sentence form, it can be very verbose. Consider the example of "The set of numbers 1 through 10".  Most of the time, people understand what is meant, but in mathematics, we want to be precise.  Consider the following statements:

* Does this is include 1 and 10?  If so, we may want to say "The set of numbers from 1 to 10 inclusive."
* What about the number $$\pi$$?  Is it included?  If not, we may want to say "The set of integers from 1 to 10 inclusive."

As you can see, precision can be implemented in sentence form, but it can be very wordy.  When  mathematician is speaking to an audience well-familiar with the topic, then sentence form is utilized with the understanding that the audience will fill in the gaps.  However, this is very clumsy. 

Sentence form is often the form to be avoided when precision is necessary.

## Roster Form

Think about a roster for a classroom.  The roster is an explicit list of the students in the class. We can determine who is an element of the class and who is not by simply looking at the roster.

Roster form for mathematical sets is very similar to a classroom roster.  The elements are explicitly listed.  

Consider the set $$A = \{2,4,6,8\}$$.  Obviously, the set is small so writing out the elements is not an issue.  However, this would be very cumbersome if we wanted to represent the set of even numbers greater than zero and less than 100. Fortunately, there is a clear pattern to the elements of the set.  Even though sets do not contain order, we can appeal to order to help make the notation more concise. 

Now consider another set shown below.
$$B = \{2,4,6, \dots, 98\}$$  Notice the pattern was established and the ellipsis was used to indicate the continuation of the pattern. Notice how the number 98 was used  to indicate where the pattern terminates. 

Consider the full set of even numbers greater than zero.  This set contains an infinite number of elements.  We can still use roster notation to represent this set.  

$$C = \{2,4,6,8,\dots\}$$  

Notice that the ellipsis is used to indicate the continuation of the pattern without a terminating element.

There are situations where roster form is not useful.  There are infinite sets where iterating through the elements does not establish a clear pattern.

Consider the set below.

$$D = \{1,2,4,8,16,32,\dots\}$$

A pattern can be established, but depending on the audience, it may not be clear.  However, mathematicians may represent the values in a different fashion to help make the pattern more obvious.

$$D = \{2^0, 2^1, 2^2, 2^3, 2^4, 2^5, \dots\}$$

When do we use roster form?

* When the set is small and listing the elements is not cumbersome.
* When the set is large (or infinite) but a clear pattern can be established.


## Set-Builder Notation

Set-builder notation is the preferred way to represent sets when the elements are best described by their construction. Set-builder notation is very much like a recipe for constructing the elements of a set.  Like a typical baking recipe, there is a list of ingredients and a set of instructions for how to combine the ingredients. 

Consider the set of even numbers greater than zero and less than 100.  We can represent this set in roster form as shown below.

$$E = \{2,4,6, \dots, 98\}$$

Alternatively, we can represent this set in set-builder notation as shown below.

$$E = \{2x \mid x \in \{1,2,3,\dots,49\}\}$$

The left side of the vertical bar is the instructions of the recipe.  The right side of the vertical bar is the list of ingredients.  

If we were to convert the set-builder notation to sentence form, we would see how the recipe is utilized. 

$$E = \{\underbrace{2 \cdot 1}_{2}, \underbrace{2 \cdot 2}_{4}, \underbrace{2 \cdot 3}_{6}, \dots, \underbrace{2 \cdot 49}_{98}\}$$

Notice the number two (left side of vertical bar) is multiplied by all the values from 1 to 49 (right side of vertical bar).

In mathematics, we often take simple elements and use them to construct more complex elements. This is why set-builder notation is so commonly used.  We can identify elements of a large set by analyzing their construction. We can decompose complex elements into their simpler components for analysis. 

Mastering set-builder notation is key for understanding the language of mathematics.  It takes time and practice to become proficient with set-builder notation.
