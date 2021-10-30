#chapter10
## Definition
A dynamical system $F$ depends sensitively on initial conditions if there is a $\beta >0$ such that for any $x$ and any $\epsilon > 0$ there is a $y$ within $\epsilon$ of $x$ and a $k$ such that the distance between $F^{k}(x)$ and $f^{k}(y)$ is at least $\beta$.

No matter which $x$ we begin with and no matter how small a region we choose about $x$, we can always find a y in this region whose orbit eventually separates from that of $x$ by at least $\beta$

## Remarks on SDIC
1. The definition of sensitivity does not require that the [[orbit]] of $y$ remain far from $x$ for all interations. We only need one point on the [[orbit]] to be far from the corresponding iterate of $x$.
2. There are other possible definitions of sensitive dependence. For example, one common definition requires that certain nearby orbits diverge exponentially. That is, it is sometimes required tha tthe distance between $F^{k}(x)$ and $F^{k}(y)$ grow like $C\mu^{k}$ for some $\mu >1$ and $C > 0$
3. The concept of sensitive dependence on inital conditions is very importatnt notion in the study of applications of dynamical systems. If a particular system possesses sensitive dependence, the for all practical purposes, the dynamics of this system defy numerical computation. Small errors in computation that are introduced by round-off may throw us off the intended [[orbit]]. Then these errors may become magnified upon iteration. Also, as always happens in real-life systems, we can never know the exact initial point of our system to matter how many didgits of accuracy we use. As a consequence, we may be looking at an orbit that eventually diverges from the true [[orbit]] we seek. Therefore, the results of numerical computation of an orbit, no matter how accurate, may bear no resemblance whatsoever to the real orbit.

## Example
The function $C(x) = \cos x$ possesses no sensitivity to initial conditions whatsoever. Indeed, as we saw, all [[orbit]]s of $C$ tend to the attracting fixed point at 0.73908$\dots$ 

On the other hand, $F(x) = \sqrt{x}$ has sensitive dependence at 0. Although 0 is a fixed point, any nearby point has [[orbit]] that tends to the attracting fixed point at 1, hence "far away". On the other hand, there is no sensitive dependence in the interval $0 < x < \infty$.


To see that the shift map depends sensitively on initial conditions, we select $\beta = 1$. For any $s\in \sum$ and $\epsilon > 0$ we again choose $n$ so that $1/2^{n} < \epsilon$. Suppose $t\in \sum$ satisfies $d[s,t] < 1/2^n$ but $t\neq s$ there is $k>n$ such that $s_k \neq t_k$. So $\vert s_k - t_k\vert = 1$. Now consider the seequences $\sigma^k (s)$ and $\sigma^k (t)$. The initial entries of each of these sequences are different, so we have
$$d[\sigma^k (s), \sigma^k (t)]\geq\frac{\vert s_k - t_k\vert}{2^0} + \sum_{i=1}^{\infty}\frac{0}{2^i} = 1$$ Then we have sensitivity for the shift map.