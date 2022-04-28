# On an extension of Polya’s Positivstellensatz
Created: 2022-03-28 10:38


### Propositions 3.3 (Epsilon-relaxation)
Let $f_0$ to be a homoheneous polynomial such that $f_0(x) > 0$ for all $x \in \mathcal X$ where $\mathcal X$ is a compact semialgebraic set. Then for any homogeneous polynomial $h \in \mathbb R[x]$ such that $deg(h) = deg(f_0)$, there exists $\epsilon > 0$ such that $f_0(x)-\epsilon h (x) > 0$  for all $x \in \mathcal X$.
#### Proof
Let $h(x) \neq 0$ for all $x \in \mathcal X$. Let $min_\mathcal X (f_0)$ be the minimum of $f_0$ over $\mathcal X$ and $max_\mathcal X (h)$ the maximum of $h$ over $\mathcal X$.  Both exist because $\mathcal X$ ist compact. We can define $\epsilon$ as follows. $$\epsilon = \frac {min_\mathcal X (f_0)}{2max_\mathcal X (h)}$$


### Theorem 3.5 (Dickinsons's Positivstellensatz)
Let  $m \in \mathbb{Z}_{++}$ and $f_0, \dots, f_m \in \mathbb R[x]$  be homoheneous polynomials of degree on $\mathbb R ^n$ such that $f_0(x)>0$ for all $x \in \cap_{i=1}^m f_i^{-1} ( \mathbb R_+) \ \{0\}$ and $f_1(x) \equiv 1$. Then for some $r \in \mathbb Z_+$ there exists homegeneous polynomials $g_1, \dots, g_m \in \mathbb R[x]$ such that all their coefficients are non-negative and $\| x \|_1^r f_0 (x) \equiv \sum_{i=1}^m f_i(x)g_i(x)$. 
#### Proof
First an Outline of the Proof
##### Outline


## Tags



## References
1.  [On an extension of Polya’s Positivstellensatz, Peter J. C. Dickinson, Janez Povh](https://link.springer.com/article/10.1007/s10898-014-0196-9)