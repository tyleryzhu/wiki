**Matrix multiplication** defines an operation on two matrices $A$ and $B$ given that $A$ is an $m \times n$ matrix and $B$ is a $n \times p$ matrix. If $C=AB$, then

\\[
C_{ij} = \sum_{k=1}^n A_{ik}B_{kj}
\\]

If it is possible to take the product $AB$, it must be the case that you can take the product $B^\mathsf{T}A^\mathsf{T}$, and, in fact, 

\\[
\left(AB\right)^\mathsf{T} = B^\mathsf{T}A^\mathsf{T}
\\]