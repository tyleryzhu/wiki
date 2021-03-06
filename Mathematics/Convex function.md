A **convex function** is a function $f$ whose epigraph is a [[convex set]]. 

Epigraph
: The **epigraph** of a [[function]] $f: \RR^n \to \RR $ is the [[set]] $$\{(x, t) \vert x \in \operatorname{dom} f; f(x) \leq t \}$$


Concretely, the domain of $f$ is a convex set and

$$
f(\theta \vec{x} + (1-\theta) \vec{y}) \leq \theta f(\vec{x}) + (1-\theta)f(\vec{y})
$$

What makes convex functions useful is that any point with gradient 0 is guaranteed to be a global minimum.

The second-order condition says that a twice differentiable $f$ will be convex if its domain is convex and its Hessian is PSD.