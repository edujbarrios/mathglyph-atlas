# Lambda Calculus

## Lambda Calculus Notation

| Name | Rendered Symbol | LaTeX Code |
|---|---|---|
| Lambda Abstraction | λx.M | `\lambda x.\,M` |
| Function Application | M N | `MN` |
| Beta Reduction | (λx.M)N → M[x:=N] | `(\lambda x.\,M)N \to M[x:=N]` |
| Eta Reduction | λx.(Mx) → M | `\lambda x.\,(Mx) \to M` |
| Alpha Conversion | λx.M ≡ λy.M[x:=y] | `\lambda x.\,M \equiv_\alpha \lambda y.\,M[x:=y]` |
| Free Variables | FV(M) | `\mathrm{FV}(M)` |
| Bound Variables | BV(M) | `\mathrm{BV}(M)` |
| Substitution | M[x:=N] | `M[x:=N]` |
| Normal Form | NF(M) | `\mathrm{NF}(M)` |
| Beta-equivalence | M =β N | `M =_{\beta} N` |
| Eta-equivalence | M =η N | `M =_{\eta} N` |
| Church Numeral 0 | λf.λx.x | `\lambda f.\lambda x.\,x` |
| Church Numeral n | λf.λx.fⁿx | `\lambda f.\lambda x.\,f^n x` |
| Boolean True | λx.λy.x | `\lambda x.\lambda y.\,x` |
| Boolean False | λx.λy.y | `\lambda x.\lambda y.\,y` |
| Fixed-Point Combinator | Y | `Y=\lambda f.(\lambda x.f(xx))(\lambda x.f(xx))` |
| Typed Arrow | A→B | `A \to B` |
| Turnstile for Typing | Γ ⊢ M:A | `\Gamma \vdash M:A` |
| Product Type | A×B | `A \times B` |
| Sum Type | A+B | `A + B` |
