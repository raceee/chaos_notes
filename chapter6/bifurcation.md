#chapter6
Let $Q_c (x) = x^2 +c$ denote the family of [[quadratic function]]s. Remember that $c$ is the parameter. The goal is to see how $Q_c$ changes as the parameter $c$ changes. 

Using the quadratic function we obtain the two [[fixed point]]s of $Q_c$ $$p_+ = \frac{1}{2}(1+\sqrt{1 - 4c})$$ $$p_- = \frac{1}{2}(1-\sqrt{1 - 4c})$$ Here if $c > 1/4$ then there are no fixed points. When $c\leq 1/4$ then $p_{\pm}$ are real. When $c= 1/4$ the $p_+ = p_- = 1/2$. 

As $c$ decreases from a large postive number we have no fixed points until $c = 1/4$. The moment that $c$ becomes less than $1/4$ then we encounter our first *bifurcation*.

For any quadratic we can check if $p_{\pm}$ is [[attracting_repelling]] by $$Q'_c (p_+ ) = 1 + \sqrt{1-4c}$$
$$Q'_c (p_- ) = 1 - \sqrt{1-4c}$$

## The First Bifurcation
For the family $Q_c (x) = x^2 + c$
1. All orbits tend to infinity if $c > 1/4$
2. When $c = 1/4$, $Q_c$ has a single fixed point at $p_+ = p_- = 1/2$ that is neutral.
3. For $c < 1/4$, $Q_c$ has two fixed points at $p_+$ and $p_-$. The fixed point $p_+$ is always repelling.
	1. If $-3/4 < c < 1/4$, $p_-$ is attracting
	2. If $c = -3/4$, $p_-$ is neutral
	3. If $c < -3/4$, $p_-$ is repelling