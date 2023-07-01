---
layout: page
title: Why nonlinear?
---

## Why nonlinear?
### Linear dynamical system
A linear dynamical system is defined as

$$ \frac{{\rm{d}}x}{{\rm{d}}t}=Ax(t), $$

where $x(t)$ is a state of this system at time $t$, and $A$ determines the relation from $x(t)$ to $x(t+{\delta}t)$. Suppose the state $x(t)$ is characterised by $d$ numeric variables, i.e., $x(t)\in\mathbb{R}^{d}$. We denote $x(t)$ as a column vector, and then $A$ is a square matrix of size $d$.

Importantly, we can solve this system analytically. A particular solution is found as

$$ x(t)=e^{At}, $$

so the general solution is

$$ x(t)=e^{At}c $$

where $c$ is an arbitrary constant vector. Then, clearly

$$ x(t)=e^{At}x(0). $$

Furthermore, discretising the time by $t=k{\Delta}t$, for $k\in\mathbb{N}\cup\\{0\\}$, yields

$$
\begin{aligned}
x(k{\Delta}t)&=e^{Ak{\Delta}t}x(0) \\
&=\left(e^{A{\Delta}t}\right)^{k}x(0) \\
x(k)&=B^{k}x(0),
\end{aligned}
$$

where $B=e^{A{\Delta}t}$.
