#chapter10 
## Dense Set
Suppose $X$ is a set and $Y$ is a subset of $X$. We say that $Y$ is *dense* in $X$ if, for any point, $x\in X$, there is a point $y$ in the subset $Y$ arbitrarily close to $x$. A set being dense is one of the [[properties of chaos]].

#### Example
* The subset of rational numbers is dense in the set of real numbers.

* The subset consisting of all irrational numbers is dense in the set of real numbers

##### Worked example
Let's prove that the rational numbers are dense in $\mathbb{R}$, we must fin da seequence of rationals convergin to any irrational. For instance, if the irrational is $\sqrt{2}$, a sequence of rationals convergin to this number is $$1,1.4 ,1.41, 1.414$$ In the general case, we begin by selecting an arbitrary real number $x$. If $x$ is rational, then we are done, so we assume that $x$ is irrational. This means that $x$ has infinite decimal expanion of the form: $$x = a_n \dots a_0 . b_1 b_2 b_3\dots$$ where the $a_j$ and $b_j$ are digits ranging from 0 to 9. Now, for $j = 1,2,3,\dots$ set $$x_j = a_n \dots a_0 . b_1 \dots b_j$$ Since $x_j$ has a finite decimal expansion, $x_j$ is a rational number. Clearly $x_j \rightarrow x$ as $j\rightarrow\infty$. So we ahve found a sequence of rational numbers that convergest to $x$. 

---

##### Why the shift map is dense
Claim: The subset of the shift map that contains all the periodic points is a [[dense]] subset

Goal: We must show that, given any point $s = (s_0 s_1 s_2\dots  )$ in $\sum$, we can find a periodic point arbitrarily close by. Suppose we are given an $\epsilon > 0$. 

How do we find a periodic point within $\epsilon$ of $s$? Let's choose an integer $n$ so that $1/2^n < \epsilon$. We may now write down an explicit periodic point within $1/2^n$ units of $s$. Let $t_n = (s_0 s_1 \dots s_n \overline{s_0 s_1 s_2\dots s_n}$. The first $n+1$ entries of $s$ and $t_n$ are the same. By the [[proximity theorem]] this means that $$d[s,t_n ]\leq\frac{1}{2^n} < \epsilon$$ But $t_n$ is a repeating seequence and so it is a periodic point of period $n +1$ for $\sigma$. since $\epsilon$ and $s$ were arbitrary, we have succeeded in finding a periodic point aribirariily close to any point in $\sum$. Note that the sequence of sequences $\{t_n \}$ converges to $s$ as $n\rightarrow\infty$.