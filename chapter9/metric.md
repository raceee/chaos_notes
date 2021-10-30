#chapter9 
Specifically in terms of the [[sequence space]], we need a way to compare 'distance' for any two elements of the set even when that set is not numbers like in $\sum$. We do this by defining a *metric* on the [[sequence space]]. 
---
## Definition
Let $s = (s_0 s_1 s_2 \dots )$ and $t = (t_0 t_1 t_2 \dots )$ be two points in $\sum$. The *distance* between $s$ and $t$ is given by

$$d[s,t] = \sum_{i = 0}^{\infty}\frac{|s_i -t_i |}{2^i}$$

Note that the series defining $d[s,t]$ always converges. Indeed, $s_i$ and $t_i$ are each either 0 or 1, so $|s_i - t_i | = 0$ or $1$. Therefore, this series is dominated by the geometric series $\sum_{i=0}^{\infty}(1/2)^i$, which converges to $2$. Thus the farthest apart any two points in $\sum$ may be is $2$ unites, as in the first example above.

---

## Definition
A funciton $d$ is called a metric on a set $X$ if for any $x,y,z\in X$ the following three properties hold:
1. $d[x,y]\geq 0$, and $d[x,y] = 0$ if and only if $x=y$
2. $d[x,y] = d[y,x]$
3. $d[x,z] \leq d[x,y] + d[y,z]$

The pair $X,d$ is called a metric space.

---
## The Proximity Theorem
Let $s,t\in \sum$ and suppose $s_i = t_i$, for $i = 0,1,\dots ,n$. Then $d[s,t] \leq 1/2^n$. Conversely, if $d[s,t] < 1/2^n$, then $s_i = t_i$ for $i\leq n$.

