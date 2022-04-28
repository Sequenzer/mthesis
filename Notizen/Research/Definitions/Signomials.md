# Real Algebra
Created: 2022-03-28 10:24

## Definitions:

### Monomials:
A ***monomial*** is a basis-function $e^\alpha : \mathbb{R}^n \rightarrow \mathbb{R}$ definied by $$e^\alpha(x) = e^{\langle \alpha , x \rangle }$$
^1f25d3
### Signomials:
A ***signomial*** is a finite product or a  real linear combination of [[#Monomials]].

### Signomial Ring:
The ***signomial ring*** over $\mathcal{A}$ is the set of all [[#Signomials]] created with $\alpha \in \mathcal{A}$  and is denoted by $\mathbb{R}[\mathcal{A} ]$ . The signomial ring is a $\mathbb{R}$-Algebra [[Algebraic Definitions#K-Algebra|(Algebra)]].

## Posynomial:
A ***posynomial*** is a [[#Signomials]] with only nonnegative terms.

---
## Propertiesof Signomials:

## X-AGE
A [[Signomials#Signomials|signomial]] is called ***X-AGE*** if it is nonnegative on $\mathcal{X} \subset \mathbb{R}^n$ and has at most one negative coefficient.

## X-SAGE
A [[Signomials#Signomials|signomial]] is called ***X-SAGE*** if it can be written as a sum of [[#X-AGE|X-AGE]] signomials.


## AGE and SAGE
A [[#Signomials|signomial]] is called ***SAGE/AGE*** if $\mathcal{X} = \mathbb{R}^n$ [[#X-SAGE|(X-SAGE)]].

## Posynomial


---
## Grading signomial rings

### Support
The ***support*** of a signomial f, denoted by $supp(f)$ is the smallest set $A \subset \mathbb{R}^n$ for which $f \in \langle e^\alpha \rangle_{\alpha \in A}$[[Algebraic Definitions#Span|(Span)]]. 

### Degree of Signomials

The $\mathcal A$-degree of a signomial f ist the smallest integer d for which $supp(f) \subset \mathcal{A}_d$. We use, $$\mathcal{A}_d = \left \lbrace \sum_{\alpha \in \mathcal A } w_\alpha \alpha : w \in \mathbb{N}^{\mathcal A }, \lVert w \rVert_1 \leq d \right \rbrace$$ is the set of linear combinations with coefficients in the $d$-square. The $\mathcal A$-degree is denoted by $deg_\mathcal A (f)$.

### Signomials of at most Degreee d
$\mathbb R [\mathcal A]_d$ denotes the space of signomials with $\mathcal A$-degree at most $d$.

### Useful Rules for the degree

The degree can be calculated by $$deg_\mathcal A (f) = max \lbrace deg_ \mathcal A ( e ^\alpha ) : \alpha \in supp(f) \rbrace$$ and $$deg_ \mathcal A (e^\alpha) = inf \left \lbrace l : l \geq 1\ \text {and} \ w \in \mathbb N ^\mathcal A  \ \text {satisfy} \ \lVert w \rVert_1 \leq l \ \text {and} \sum_{\beta \in \mathcal A} \beta \cdot w_\beta = \alpha \right \rbrace \ $$
#### Degree under Multiplikation

For any signimial $f,g$ in a ring $\mathbb R [\mathcal A ]$, we have $$deg_\mathcal A (fg) \leq deg_\mathcal A(f) + deg_\mathcal A(g)$$
## Generalized Polynomials
Alternatively we can define [[#Signomials]] as a generalization of [[Polynomials]]. $$ f(x)= \sum_{i=0}^m c_ix^{\alpha_i}$$ with $\alpha_i = (\alpha_1,\dots,\alpha_n) \in \mathbb{R}^n$.

> Look into the Translations between the Definitions!!

---

## Tags

#Signomials #SAGE 

## References
1.  [Algebraic perspectives on signomial optimization, Mareike Dressler, Riley Murray](https://arxiv.org/abs/2107.00345)




