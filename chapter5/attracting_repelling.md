#chapter5 
There are two different types of [[fixed point]]s, attracting and repelling fixed points. 

## Definition
$x_0$ is an attracting fixed point if $$|F'(x_0 )|<1$$
$x_0$ is an repelling fiex point if $$|F'(x_0 )|>1$$
$x_0$ is a neutral or indifferent fixedpoint if $$|F'(x_0 )| = 1$$

This is true because of two corollaries from the [[mean value theorem]]

## Theorem - Attracting Fixed Point Theorem
Suppose $x_0$ is an attracting fixed point for $F$. Then there is an interval $I$ that contains $x_0$ in its interior and in which the following condition is satisfied: 
If $$x\in I, \quad then\quad F^{n}(x)\in I,\quad\forall n$$and, moreover, $$F^{n}(x)\rightarrow x_0\quad as\quad n\rightarrow\infty$$

## Repelling Fixed Point Theorem
Suppose $x_0$ is a repelling fixed point for $F$. Then there is an interval $I$ that contains $x_0$ in its interior and in which the follwoing condition is statisfied: 
If $$x\in I \quad and \quad x\neq x_0$$ then there is an integer $n>0$ such that $$F^n (x) \notin I$$

## Neutral Fixed Point Theorem
(Left as exercise)

## Chain Rule Along a Cycle
Suppose $x_0 , x_1 , \dots , x_{n-1}$ lie on a cycle of period $n$ for $F$ with $x_i = F^{i}(x_0 )$. Then: $$(F^n )'(x_0) = F'(x_{n-1})\dots F'(x_1 )F(x_0 )$$ This tells us that the derivative of $F^{n}(x_0)$ is simply the product of the derivatives of $F$ at all points on the [[orbit]].

## Chain Rule On Cycle Corollary
Suppose $x_0 , x_1 ,\dots x_{n-1}$ lie on an n-cycle for F. Then $$(F^{n})'(x_0) = (F^n)'(x_1 ) =\dots =(F^n)'(x_{n-1})$$