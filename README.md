# Learning the potential of a conservative vector field

We want to produce an approximation (up to an additive constant) of a potential $S:\mathbb{R}^n\to\mathbb{R}$ via samples from its gradient field $s:=\nabla S :\mathbb{R}^n\to\mathbb{R}^n$.

We use the example
$$S:\mathbb{R}^2 \ni x \mapsto e^{-\frac{1}{2}\|x\|^2} \in \mathbb{R},$$
for which we have
$$s:\mathbb{R}^2 \ni x \mapsto -x e^{-\frac{1}{2}\|x\|^2} \in \mathbb{R}^2.$$

We do this by using pytorch and illustrate the results via fantastically inefficient plot generation.