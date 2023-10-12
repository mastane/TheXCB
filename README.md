# The cross convex bestiary

## Visualization of Lemma 1 in https://arxiv.org/abs/2309.15298
* Open the notebook "XCB_Gen" and select your favorite log-concave function $p$ in the dropdown menu
* Compute cross-convex function $F(x,y)=-\log(p(x)+p(y))$ 
* Tangent lower bound
$$
\mathcal{T}_{a,b}(x, y) = F(a,b) + \nabla F(a,b)^\top \begin{pmatrix} x-a \\ y-b \end{pmatrix} - D_{\text{KL}}\left( \begin{pmatrix} \frac{p(a)}{p(a)+p(b)} \\ \frac{p(b)}{p(a)+p(b)} \end{pmatrix} \, \Bigg\| \, \begin{pmatrix} \frac{p(x)}{p(x)+p(y)} \\ \frac{p(y)}{p(x)+p(y)} \end{pmatrix} \right)
$$
