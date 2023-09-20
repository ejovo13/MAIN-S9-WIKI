# Worked Exercises

This page will *attempt* to provide corrections [TD exercises](course_material.md). There are *no guarentees* that any of the material in this section is accurate.

## TD1 - Stable maximum dans un graphe

### Statement

Convert the combinatorial problem of finding a maximal independent set into an integer optimization problem.

### Model

We represent a unique independent set using binary decision variables, and then we impose arithmetic constraints that are equivalent to the graph definition of an independent set.


#### Variables

- $G = \langle V, E \rangle$
- $\chi =$ indicator vector for the vertices $u \in V$

#### Constraints

We need to translate the definition of "no two vertices share an edge" into a set of arithmetic equations.

- $x_u + x_v \le 1, \quad uv \in E$
- $x_u \in \{0, 1\}, \quad u \in V$

#### Objective function

We want to find the set with the maximum number of vertices, which lends itself to the following objective function:

$$\sum_{u \in V}x_u$$

---

## TD2 - Couplage maximum dans un graphe

### Statement

Convert the combinatorial problem of finding a maximal matching into an integer optimization problem.

### Model

#### Variables

- $G = \langle V, E, \rangle$
- $\chi =$ indicator vector for the edges $e \in E$