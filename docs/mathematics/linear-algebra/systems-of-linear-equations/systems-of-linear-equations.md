---
title: Systems of Linear Equations
layout: default
parent: Linear Algebra
nav_order: 1
has_children: true
---

# Systems of Linear Equations

Systems of linear equations (SLE) are a collection of one or more linear equations involving the same set of variables.  The goal is to find values (solutions) for the variables so that the values satisfy all of the equations in the system.  SLEs are fundamental in linear algebra and have applications in various fields such as physics, engineering, computer science, and economics.

## Equations Tell Pieces of a Story

Each equation in an SLE provides a piece of information about the variables.  It effectively offers an incomplete vantage point on the solution.  When we have multiple equations that are part of the SLE, we can combine the information from all of the equations to get a more complete picture of the solution. The more equations we have, the more information we have about the solution.  

The scenario is very much like a detective trying to solve a mystery. Each equation provides a clue.  Individually, no single equation may be sufficient to solve the mystery (solution), but taken together, the equations provide enough information to solve the mystery.  Restated, each equation provides some vantage point about the solution.

## Types of Solutions

SLEs fall into one of three categories.  Every SLE will fit into exactly one of these categories:

1. **No solution**: The equations are inconsistent and cannot be satisfied simultaneously.  This is like a detective having contradictory clues that cannot all be true at the same time.
2. **Exactly one solution**: The equations are consistent.  Each equation provides a unique vantage point and together they provide the entire picture. A solution not only exists, but the solution is the only feasible solution.  This is like a detective having consistent clues that point to a single suspect, allowing them to solve the mystery conclusively.
3. **Infinitely many solutions**: The equations are consistent. However, the equations do not provide enough information to determine a unique solution.  Solutions can be ruled out, but are will be infinitely many solutions that satisfy the equations.  This is like a detective having consistent clues that point to a group of suspects, but not enough information to single out one suspect as the culprit.

To be clear, the above are the only possible outcomes.   It is not possible for an SLE to have exactly two solutions, or exactly three solutions, etc.  The solution set of an SLE is either empty (no solution), a single point (exactly one solution), or an infinite set (infinitely many solutions).

## Example

This section will contain an example for each of the three categories of SLEs.  The examples will be simple.


### Unique Solution Example

Let's consider an example of an SLE that has exactly one solution.  This means that there is a unique tuple of values for the variables  that satisfies all of the equations in the system.

Consider the following SLE:

$$
\begin{cases}
x + y = 2 \\
3x - 2y = 5
\end{cases}
$$

The first equation indicates that the sum of $x$ and $y$ must equal 2. Notice there are infinitely many pairs of $(x,y)$ that satisfy this equation.  For example, $(1,1)$, $(0,2)$, and $(-1,3)$ all satisfy the first equation.

The second equation indicates that three times $x$ minus two times $y$ must equal 5.  Notice there are infinitely many pairs of $(x,y)$ that satisfy this equation as well.  For example $(1, -1)$ and $(3, 2)$ both satisfy the second equation.

However, when we consider that both equations must be satisfied simultaneously, by the same values of $x$ and $y$, we can find a unique solution.  The solution is shown below.

$$(x,y) = \left(\frac{9}{5}, \frac{1}{5}\right)$$

Notice the graph below provides a visual representation of the solution.  Each line represents one of the equations in the SLE.  The point where the two lines intersect is the unique solution to the SLE.

<img src="/assets/images/mathematics/linear-algebra/sle/sle_intersection_lines.png" alt="Unique Solution" style="max-width: 600px; width: 100%;">

The green line represents the equation $x + y = 2$.

The blue line represents the equation $3x - 2y = 5$.

The intersection of the two lines is the unique solution to the SLE.  The coordinates of the intersection point are $\left(\frac{9}{5}, \frac{1}{5}\right)$, which is the solution to the SLE.  This means that when $x = \frac{9}{5} = 1.8$ and $y = \frac{1}{5} = 0.2$, both equations are satisfied simultaneously.

### No Solution Example

Now let's consider an example of an SLE that has no solution.  This means that there are no values for the variables that can satisfy all of the equations in the system simultaneously.

Consider the following SLE:

$$
\begin{cases}
x + y = 2 \\
x + y = 3
\end{cases}
$$  

The first equation indicates that the sum of $x$ and $y$ must equal 2.  The second equation indicates that the sum of $x$ and $y$ must equal 3.  Notice that these two equations are contradictory.  There are no values for $x$ and $y$ that can satisfy both equations at the same time.  Therefore, this SLE has no solution.

The graph below provides a visual representation of the solution.  Each line represents one of the equations in the SLE.  Notice that the lines are parallel and do not intersect, which visually confirms that there is no solution to the SLE.

<img src="/assets/images/mathematics/linear-algebra/sle/sle_no_solution_lines.png" alt="No Solution" style="max-width: 600px; width: 100%;">

### Infinitely Many Solutions Example

Finally, let's consider an example of an SLE that has infinitely many solutions.  This means that there are infinitely many values for the variables that can satisfy all of the equations in the system simultaneously.

Consider the following SLE:

$$
\begin{cases}
x + y = 2 \\
2x + 2y = 4
\end{cases}
$$  

The first equation indicates that the sum of $x$ and $y$ must equal 2.  The second equation is simply the first equation multiplied by 2.  This means that the second equation does not provide any new information beyond what is already provided by the first equation.  Therefore, there are infinitely many pairs of $(x,y)$ that satisfy both equations simultaneously.  For example, $(1,1)$, $(0,2)$, and $(-1,3)$ all satisfy both equations.

The graph below provides a visual representation of the solution.  Notice it appears as though only one line is present.  This is because the two equations represent the same line.  Every point on the line satisfies both equations, which visually confirms that there are infinitely many solutions to the SLE.

<img src="/assets/images/mathematics/linear-algebra/sle/sle_infinite_solutions_lines.png" alt="Infinite Solutions" style="max-width: 600px; width: 100%;">

It is important to note that infinite solutions does not mean every possible value for $x$ and $y$ is a solution.  Only the values of $x$ and $y$ that lie on the line are solutions.  The system did constrain the solution set, but it did not constrain the solution set to a single point.  The solution set is an infinite set of points that lie on the line.

