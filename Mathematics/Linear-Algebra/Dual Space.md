Every [[vector space]] $V$ has a **dual (vector) space** $V^*$ which is simply the [[homomorphism]] $\operatorname{Hom}(V, \mathbb{R})$, the set of linear maps from $V$ to $\RR$. Its elements are variously called **covectors** or **dual vectors**.

We may well ask for a basis for $V^\*$. As a matter of economy, we allow the choice of basis vectors $\vec{e}\_1, \ldots, \vec{e}\_n$ for $V$ to determine the basis for $V^\*$.

\begin{equation}
\epsilon^i(\vec{e}_j) = \delta^{i}_j
\end{equation}

# Double dual

Consider $V^{**}=(V^\*)^\*$. An element $\Phi$ of $V^{\*\*}$ will take in a function $f: V \to \mathbb{R}$ and produce a number. How do we do this? Simply feed in an element $\vec{v} \in V$. So,

$$
\Phi_\vec{v}(f) = f(\vec{v})
$$

**Fact**. If $\dim V < \infty$, then $V^{**} \cong V$ because the above is an isomorphism.