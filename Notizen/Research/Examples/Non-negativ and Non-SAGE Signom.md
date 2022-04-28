# Non-negativ and Non-SAGE Signom
Created: 2022-03-28 10:44






Let $P$ and $N$ the set of all indeces with positive/negative coefficients.
$$f(x)= \sum_{j \in P } c_j x^{\alpha_j} + \sum_{j \in N} c_j x^{\alpha_h}$$

### Approach 1

#### Lemma 1 (doesn't work)

#### Lemma 2
$$f(x) = \left\vert c \right\vert x^m - \sum_{j\in P} c_j x^{\alpha_j} + \left\vert c \right\vert x^n >0 \ \forall x\in \mathbb{R_\geq}$$
With $c=(c_1,\dots,c_n) \in \mathbb{R}_\geq^n$ and $m > max \lbrace \alpha_j \ \vert \  j \in P \rbrace$, $n < min \lbrace \alpha_j \ \vert \  j \in P \rbrace$.

> - Polynomials of this form are always SAGE and non-negative.
> - Every non-negative homogenous Signomials is SAGE?!
> - Transate to [[Signomials#Signomials|exponential Form]]!!!




### Approach 2 (Theobald)

Let $h$ be a univariate [[Signomials#Signomials|signomial]] and a sum of two [[Signomials#AGE and SAGE|AGE]] signomials $f$ and $g$. $$f(x):= c_1exp(\alpha_1x) + c_2exp(\alpha_2x)  + c_3exp(\alpha_3x)$$ $$g(x):= f(-x)$$ with [[Signomials#Support|support]] points $\alpha_1 =1, \ \alpha_2 = 2$ and $\alpha_3 = 3$. Let $c_1 +c_2 +c_3 =1$ enforce that $f(0)=1$. Furthermore let $f(1)=0,\ f'(1)=0$ .

With these constraints we get to Extrema $h(1)=h(-1)$ . Which means $$h_1(x)=h(x)-h(1)$$ is  not [[Signomials#AGE and SAGE|SAGE]] 

>- How does having two mimima enforce non SAGE???
>- How does this translate to [[Signomials#Generalized Polynomials|generalized polynomials]]???

## Going Further....

First we only consider [[Signomials#Signomials|signomials]] in one variable.
### Monomial Case

For every [[Signomials#Monomials|monomial]] $p=c_\alpha e^{\alpha x}$ with  $1<\alpha \in \mathbb{R}$ and $0<c_{\alpha} \in \mathbb{R}$. We notice that $$f(x)=c_3e^{(\alpha+1)x}-p+c_1e^{(\alpha-1)x}>0 \ \forall x \in \mathbb{R}$$ and $$f(x)+f(-x)-f_{min} > 0 \ \forall x \in \mathbb R$$
is not [[Signomials#AGE and SAGE|SAGE]]. For this we take $c_3 = \frac {c_\alpha} {2e}$ and $c_1 =\frac {c_\alpha e} 2$.

#### Notes for Proof
![[Screenshot_20220413-192127_Samsung Notes.jpg]]
>ToDo: Tex Proof!!!


### Poysnomial Case
For every [[Signomials#Posynomial|posynomial]] $p=\sum_\alpha c_\alpha e^{\alpha x}$ with  $1<\alpha \in \mathbb{R}^n$ and $0<c_{\alpha} \in \mathbb{R}$. We notice that $$f(x)=c_3e^{(\alpha_>)x}-p+c_1e^{(\alpha_<)x}>0 \ \forall x \in \mathbb{R}^n$$


> - Bivariate Signomials??
> - multivariate Signomials?
## Tags
#Signomials #SAGE 


## References
1. Non published Example 