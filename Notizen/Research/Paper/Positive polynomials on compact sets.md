# Positive polynomials on compact sets
Created: 2022-04-07 14:22


Let R be a commutative ring with 1 which contains $\mathbb R$. 

### Definitions

#### semiring 
$P \subset R$ is called a *semiring* iff, $$ 0,1 \in P, \ P + P \subset P, \ P \cdot P \in P.$$ ^911707
> It is multiplicative and additive closed.

#### preprime
A [[#semiring]] $P$ is called and (infinite) *preprime* if $-1 \in P$.



#### archimedean
A [[#preprime]] $P \in R$ is called *archimedean* if for all $a\in R$ there exists an $N \in \mathbb N$ such that $$ N \pm a \in P.$$
#### representation space
given a [[#preprime]] $P \subset R$ let $$ X(P) := \lbrace \phi \in Hom(R,\mathbb R)  \ \vert \ \phi(P) \subset \mathbb R_+ \rbrace$$ be the *representation space* of $P$.

#### zero-locus
for $\mathcal a = (a_1,\dots,a_n) \subset \mathbb R [X_1,\dots,X_n]$ we call, $$ V_\mathbb R(\mathcal a) = \lbrace x \in \mathbb R^n\vert \ a_1(x) = \dots = a_k(x) = 0 \rbrace$$ the *zero-locus* of $a$. Furthermore is $$ S(P) := \lbrace x \in V_\mathbb R(\mathcal a) \vert \ f(x) \geq 0 \text{ for all } f \in P \rbrace$$ a semialgebraic set.

___
### Theorem 1 (Kadison-Dubois)

^d2a172

Let $P \in R$ be an archimedean preprime and $f \in R$. Then the following holds:
1. [[#representation space|X(P)]] is an nonempty and compact space.
2. $\forall \phi  \in X(P): \phi(f) \geq 0 \Leftrightarrow \forall N \in \mathbb N \exists k \in \mathbb N: k(1+Nf) \in P$   
#### Proof
ToDo


### Corallary 1 (genreralized Stellensatz)
Let $R = \mathbb R [X_1,\dots, X_n] /(a_1,\dots,a_n)$ and $P \subset R$ an archimedian preprime with $\mathbb Q_+ \subset P$. Then for all $f \in R$ we have: $$ f_{\vert S(P)}> 0 \Leftrightarrow \exists 0 < \epsilon \in \mathbb Q, \ p\in P: f = \epsilon +p.$$
#### Proof
[[#zero-locus|S(P)]] can be canonically identified with the close set the [[#representation space]] via $$\begin{aligned}S(P) &\rightarrow X(P) \\ x &\mapsto e_x  \end{aligned}$$ where $$\begin{aligned} e_X: R &\rightarrow \mathbb R \\ f &\mapsto f(x)\end{aligned}$$ hence $S(P)$ is non-empty and compact by [[#Theorem 1 Kadison-Dubois|Kadison-Dubois]].

Now assume $f_{\vert S(P)}> 0$. Then there exists $N \in \mathbb N$ s.t $(f-\frac 1 N)_{\vert S(P)} > 0$. By Kadison-Dubois we find  $k \in \mathbb N$ such that $$ k(1+N(f-\frac 1 N)) = k \cdot N \cdot f \in P$$ By assumption $\mathbb Q_+ \subset P$  and $f-\frac 1 N$ being strictly positive on $S(P)$ it follows that $f - \frac 1 N \in P$. Thus $$f = \frac 1 N +p$$
for some $p \in P$.  ==The converse direction is trivial?== 

## Tags



## References
1. [Positive polynomials on compact sets, Berr, Wörmann](https://www.researchgate.net/publication/226463524_Positive_polynomials_on_compact_sets)
2. [Zum Darstellungssatz von Kadison-Dubois, Becker ,Schwartz](https://link.springer.com/article/10.1007/BF01192806)