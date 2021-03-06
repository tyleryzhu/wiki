A **state-space representation** models a physical system using input, output, and state variables with a first-order differential or difference equation. 




|Type|Continuous|Discrete|
|-----|----------|--------|
|Generic|$\dv{}{t}\vec{x}(t)=f(\vec{x}(t), \vec{u}(t))$|$\vec{x}[t+1]=f(\vec{x}[t], \vec{u}[t])$|
|LTI|$\dv{}{t}\vec{x}(t) = A\vec{x}(t) + B\vec{u}(t)$|$\vec{x}[t+1]=A\vec{x}[t]+B\vec{u}[t]$|

If our model has a complicated form for $f$, we can use a linear approximation.

Equilibrium point
: A state $\vec{x}^\star$ for a constant input $\vec{u}^\star$ such that $f(\vec{x}^\star, \vec{u}^\star)=0$.

$$
A = \left[\nabla_\vec{x} f(\vec{x}, \vec{u})\right]_{\vec{x}^\star, \vec{u}^\star},\quad B = \left[\nabla_\vec{u} f(\vec{x}, \vec{u})\right]_{\vec{x}^\star, \vec{u}^\star}
$$

$$
\tilde{\vec{x}}(t) = \vec{x}(t)-\vec{x}^\star,\quad \tilde{\vec{u}}(t) = \vec{u}(t)-\vec{u}^\star,
$$

$$
\dv{}{t} \tilde{\vec{x}}(t) = \dv{}{t} \vec{x}(t) = A\tilde{\vec{x}}(t) + B\tilde{\vec{u}}(t)
$$

# Discretization

