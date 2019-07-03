A Bernoulli distribution is a discrete probability distribution modeling a possibly biased coin flip (i.e. a coin flip where heads, associated with the value 1, has probability $p \in [0,1]$).

\\[
\Pr(X=x) = \begin{cases}p & x=1 \\\  1-p & x=0\end{cases}
\\]

This can be written in a single expression as

\\[
\Pr(X=x) = p^x (1-p)^{1-x},\quad x \in \\{0,1\\}
\\]

When $x=0$, the first term is a 1 and the second term is $1-p$. Likewise, when $x=1$ the first term is a $p$ and the second term is a 1.