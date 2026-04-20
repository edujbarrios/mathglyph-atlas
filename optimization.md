# Optimization

## Optimization Symbols

| Name | Rendered Symbol | LaTeX Code |
|---|---|---|
| Objective Function | f(x) | `f(x)` |
| Minimize | min | `\min_{x} f(x)` |
| Maximize | max | `\max_{x} f(x)` |
| Argmin | argmin | `\arg\min_{x} f(x)` |
| Argmax | argmax | `\arg\max_{x} f(x)` |
| Subject To | s.t. | `\text{s.t.}` |
| Equality Constraint | g(x)=0 | `g(x)=0` |
| Inequality Constraint | h(x)≤0 | `h(x)\leq 0` |
| Lagrangian | L(x,λ) | `\mathcal{L}(x,\lambda)` |
| KKT Conditions | KKT | `\nabla_x \mathcal{L}(x,\lambda)=0` |
| Gradient | ∇f | `\nabla f(x)` |
| Hessian | ∇²f | `\nabla^2 f(x)` |
| Directional Derivative | Dᵥf | `D_{\mathbf{v}} f` |
| Step Size / Learning Rate | η | `\eta` |
| Update Rule | xₜ₊₁ | `x_{t+1}=x_t-\eta\nabla f(x_t)` |
| Convex Function | f convex | `f(\theta x+(1-\theta)y)\leq\theta f(x)+(1-\theta)f(y)` |
| Strong Convexity | μ-strongly convex | `f(y)\geq f(x)+\nabla f(x)^\top(y-x)+\frac{\mu}{2}\lVert y-x\rVert^2` |
| Lipschitz Gradient | L-smooth | `\lVert\nabla f(x)-\nabla f(y)\rVert\leq L\lVert x-y\rVert` |
| Projection | ΠC(x) | `\Pi_{\mathcal{C}}(x)` |
| Dual Function | g(λ) | `g(\lambda)=\inf_x \mathcal{L}(x,\lambda)` |
| Duality Gap | p*−d* | `p^*-d^*` |
