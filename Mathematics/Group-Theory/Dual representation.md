A **dual representation** for a [[group]] $G$ and its [[group representation]] $\rho$ on a [[vector space]] $V$ is a $\rho^\*: G \to \operatorname{GL}(V^\*)$ or, if we like, $G \times V^\* \to V^\*$ that respects the [[natural pairing|dual pair#natural pairing]]. As such, it must obey the following condition,


$$
\rho^*(g) = \rho(g^{-1})^\top
$$

Less formally, let's imagine we want to play around with transformations of a vector space $V$. If our transformations are restricted to being matrices $A$, we can link up matrix $A$ with a group element $A$. If we need to tap into $V^*$, we can make our group do double duty for us by representing the same group elements $A$ using matrix $A^{-\top}$.



# Derivation

We want to restrict ourselves to looking for $\rho^\*$ that respect the natural pairing between $V$ and $V^\*$. Consider elements $v \in V$ and $v^* \in V^\*$. They can be paired up so that $\langle v^\*, v\rangle = c$. All we're saying is that don't want our representation to mess this up:

\begin{equation}
\label{eq:nat-pair}
\langle \rho^\*(g)(v^\*), \rho(g)(v) \rangle = c = v^*(v)
\end{equation}

Now note that $\rho^\*(g)$ and $\rho(g)$ gives us matrices, which clearly will be related if Equation \ref{eq:nat-pair} is to hold. Let's just call $\rho(g)=A$ and $\rho^\*(g)=f(A)$. Note also that dual vectors eat vectors as the inner product, so

$$
(f(A) v^*)^\top Av = (v^*)^\top v \implies f(A)^\top A = I \implies f(A) = A^{-\top}
$$

<<Warn("We're treating both vectors and dual vectors as column vectors here!")>>


