#chapter3 
To iterate a function means to evaluate the function over and over, using the output of the previous application as the input for the next. This is the same process as typing a number into a scientific calculator repeatedly. If we consider the [[quadratic function]] where $c = 1$

$$F^2 (x) = F(F(x)) = (x^2 + 1)^2 + 1$$
$$F^3 (x) = F(F(F(x)))$$

Iterations create an orbit, or sequence such that 
$$F(x_0 ) = x_1$$
$$F(x_1 ) = x_2$$
$$...$$
$$F(x_{n-1}) = x_n$$

The $x_0$ value is called the *seed*.
## Types of orbits
### Fixed points 
^fixed point
A fixed point is a point $x_0$ such that $F(x_0 ) = x_0$ any function $F(x)$ has fixed points at the solutions of $$F(x) = x$$ So if $F(x) = x^2 - x - 4$ Then the fixed points are the solutions $x^2 - x - 4 = x$
### Periodic Orbit or Cycle
A point $x_0$ is periodic if $F^{n}(x_0 ) = x_0$ where $n > 0$. If the orbit is periodic then the sequence of numbers repeats after $n$ iterations. We can find periodic points by solving the equation $$F^{5}(x) - x = 0$$ Very similar to finding fixed points.

We reserve the word prime period for the case of smallest possible $n$ where there is a periodic orbit.

### Eventually fixed/periodic
If $x_0$ itself is not fixed or periodic, but some point on the orbit of $x_0$ is fixed or periodic then the orbit is *eventually fixed/periodic*