## Problem 1: 
Show that, $c\subset \ell^\infty$ is a vector subspace of $\ell^\infty$ and so is $c_0$, the space of all sequences of scalars converging to zero. 
### Solution
Recall that $ell^\infty$ denotes the space of all bounded scalar sequences, with the supremum norm. And $c$ denotes the space of all convergent sequences.
we have,  
\[
c := \{ (x_n) \in \ell^\infty : (x_n) \text{ converges} \}.
\]

Take any two sequences \( (x_n), (y_n) \in c \) and scalars \(\alpha, \beta \in \mathbb{R}\) (or \(\mathbb{C}\)).  
Define a new sequence \( (z_n) \) by  
\[
z_n = \alpha x_n + \beta y_n \quad \text{for each } n.
\]

Since \(x_n \to x\) and \(y_n \to y\) as \(n \to \infty\), let \(\varepsilon > 0\). There exists \(N \in \mathbb{N}\) such that for all \(n > N\),
\[
\|x_n - x\| < \frac{\varepsilon}{2|\alpha|}, \quad
\|y_n - y\| < \frac{\varepsilon}{2|\beta|}.
\]

Set \( z = \alpha x + \beta y \). Then, for all \( n > N \),
\[
\begin{aligned}
\|z_n - z\| 
&= \|\alpha(x_n - x) + \beta(y_n - y)\| \\
&\le |\alpha| \, \|x_n - x\| + |\beta| \, \|y_n - y\| \\
&< |\alpha| \cdot \frac{\varepsilon}{2|\alpha|} + |\beta| \cdot \frac{\varepsilon}{2|\beta|} \\
&= \varepsilon.
\end{aligned}
\]

Hence \( z_n \to z \), so \( (z_n) \in c \). Therefore, \(c\) is closed under linear combinations.  
Since the zero sequence belongs to \(c\), we conclude that \(c\) is a vector subspace of \(\ell^\infty\).

---

Now define  
\[
c_0 := \{ (x_n) \in \ell^\infty : x_n \to 0 \}.
\]

Clearly \(c_0 \subset c\). Using the same argument, sequences in \(c_0\) are closed under linear combinations. Hence, \(c_0\) is also a vector subspace of \(\ell^\infty\).
Source: Problem from the book of Kreyszig, Introductory Functional Analysis, chapter-2 Normed Spaces. Banach Spaces.
