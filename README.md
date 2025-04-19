
# IRLS repository

<!-- badges: start -->

![Static Badge](https://img.shields.io/badge/R-language-blue)
![License](https://img.shields.io/github/license/vadimtyuryaev/ANOVA)
![Static
Badge](https://img.shields.io/badge/LinkedIn-https%3A%2F%2Fwww.linkedin.com%2Fin%2Fvadimtyuryaev%2F-blue)
![Static
Badge](https://img.shields.io/badge/Medium-https://medium.com/@vadimtyuryaev-green)
<!-- badges: end -->

This repository provides a from‑first‑principles implementation of the
**Iteratively Reweighted Least Squares (IRLS)** algorithm for logistic
regression. It is designed for graduate students, advanced
undergraduates, and practitioners with a strong interest in
computational statistics, numerical optimization, and the theoretical
foundations of generalized linear models. In addition to a detailed
mathematical derivation, the repository includes annotated R code and a
real‑world case study using stock market data, offering both theoretical
insight and practical application.

You will:

1.  **Understand the exponential‑family formulation** of the binomial
    distribution, and derive the log‑likelihood, score vector, and
    Fisher information from first principles.

2.  **See how Newton–Raphson** algorithm applied to the binomial
    log‑likelihood can be recast as weighted least squares, laying the
    theoretical foundation for the IRLS.

3.  **Walk through the IRLS algorithm** with an easy-to-follow
    mathematical derivation and clear matrix formulation.

4.  **Examine an R implementation** (`IRLS_logistic_binomial`) with
    detailed annotations, illustrating how to initialize, iterate, and
    stabilize your fits in practice.

5.  **Apply IRLS to real data** (the `S&P Daily Smarket dataset`), and
    directly verify that results obtained reproduce the same
    coefficients as R’s built-in function `glm(..., family=binomial)`.

# References

<div id="refs" class="references csl-bib-body hanging-indent">

<div id="ref-dunn_smyth_glm_2018" class="csl-entry">

Dunn, Peter K., and Gordon K. Smyth. 2018. *Generalized Linear Models
with Examples in R*. 1st ed. Springer Texts in Statistics. New York, NY:
Springer Science+Business Media, LLC.
<https://doi.org/10.1007/978-1-4419-0118-7>.

</div>

<div id="ref-mccullagh_nelder_1989" class="csl-entry">

McCullagh, P., and J. A. Nelder. 1989. *Generalized Linear Models*.
London: Chapman & Hall.

</div>

</div>
