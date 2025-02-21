---
layout: page
title: Gröbner Bases for Polynomial Ideals and Applications
---

## Authors: Christian Eder, Rafael Mohr and Mohab Safey El Din

This page contains the code samples from the corresponding chapter in the OSCAR book. You can access the full chapter [here](https://link.springer.com/chapter/10.1007/978-3-031-62127-7_11).

### How to use Gröbner bases in OSCAR explained on the computation of Hilbert series

```julia
# INSERT_EXAMPLE specialized/eder-mohr-ideal-theoretic/hilbert.jlcon
```

### Computing Gröbner bases with respect to different monomial orderings

#### Applying elimination
```julia
# INSERT_EXAMPLE specialized/eder-mohr-ideal-theoretic/gbeliminate.jlcon
```
#### Using the FGLM algorithm for a change of ordering
```julia
# INSERT_EXAMPLE specialized/eder-mohr-ideal-theoretic/fglm.jlcon
```

#### Compute real solutions
```julia
# INSERT_EXAMPLE specialized/eder-mohr-ideal-theoretic/realsols.jlcon
```

### Computing non-proper points

```julia
# INSERT_EXAMPLE specialized/eder-mohr-ideal-theoretic/nonproper.jlcon
```

### Computing conormal spaces and Whitney stratifications
```julia
# INSERT_EXAMPLE specialized/eder-mohr-ideal-theoretic/whitney.jlcon
```

### An example from combinatorics
```julia
# INSERT_EXAMPLE specialized/eder-mohr-ideal-theoretic/combinatorics.jlcon
```

### Checking for local complete intersections
```julia
# INSERT_EXAMPLE specialized/eder-mohr-ideal-theoretic/lcis.jlcon
```
