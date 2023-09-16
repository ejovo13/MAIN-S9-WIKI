# Algorithmique combinatoire, optimisation

This course is dedicated to the study of combinatorial problems through the lens of optimization. Throughout the course you'll learn how to model combinatorial problems as Integer Optimization problems - and solve them using the skills acquired from Optimisation Continue.

# Introduction

There are several combinatorial problems that can be modeled as optimization problems, and then solved practically using different mathematical language implementations. Fundamentally, we are converting problems that are NP-Hard into more tractable approaches. Futhermore, the fact that these problems are combinatorial means that the entire space of realisable solutions explodes as the size of the instance increases.


## Big Ideas

One of the core ideas of this course is the transformation of combinatorial problems into optimization problems via the introduction of decision variables. Say, for example, we want to compute the independent set with maximum cardinality. For a large graph, that involves enumerating a combinatorial-increasing number of independent sets. If, however, we introduce binary decision variables and introduce numerical constraints that correspond to abstract definitions, we can hope to convert NP-Hard problems into easier optimization problems with linear objective functions and linear constraints.

## What's next