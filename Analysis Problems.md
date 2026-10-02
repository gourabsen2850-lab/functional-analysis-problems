Q.1 Let f(x) and g(x) be two uniformly continuous functions on $\mathbb{R}$. Then their pointwise product f(x)g(x) is also uniformly continuous on $\mathbb{R}$. True or False ?

Ans: we can check this through some counter examples.

 Let, f(x)=g(x)=x,   for all x $\in \mathbb{R}$. Then their pointwise product which is $x^{2}$ is not a uniformly continuous function in $\mathbb{R}$. So the above statement is false.

 Can we take another example? 

 Assume, f(x)= x and g(x)=sin x, then f(x)g(x)= x sin x , which is not a uniformly continuous function in $\mathbb{R}$. So the statement above is false, in general.


 Q2.How many zeroes does the function f(x)= $e^{x}$ - $3x^2$ have in $\mathbb{R}$ ?

 Ans:    we are finding those x for which f(x)=0 i.e. $e^x$- $3x^2$ = 0 $=>$ $x$= $log(3x^2)$. 

 And using the graph of individual functions $y=x$ and $y=log(3x^2)$, we can only see that there are three points of intersection. And this would true for all $x \in \mathbb{R}$.

Q3. Let, A be the set of all functions $f : \mathbb{R} -> \mathbb{R}$ , that satisfy the following

<div>a. f has derivative of all orders &

b.For all $x \in \mathbb{R}$,</div>

  <p align="center">
   $f(x+y)-f(y-x)=2x f'(y)$
   </p>

then, show that any $f \in A$ is a polynomial of degree less than or equal to 2.

Ans: Before we go for solutions we want to understand some characteristic that $f(x)$ has. 

Lets put y=0 in the above condition (b), we get,
<p align= "center">
  $f(x) - f(-x)= 2x f'(0)$ 
</p>
which says some kind of symmetry we are getting from this. If we recall the properties of Lagrange's Mean Value Theorem, this equation is making sense. So whatever we choose, $x \in \mathbb{R}$, the slope of the line joining $(x,f(x))$ and $(-x,f(-x))$ is always equal with $\f'(0)$. 
That tells, the sign of $f(x)$ and $f(-x)$ are same, which suffices that the function if it is a polynomial then it must be of even power. 

From the condition (a), we can see that we can expand the function using Taylor series expansion, 

<p align="center">
 $f(x) = \sum_{n=0}^{\infty} a_n x^n $
</p>
