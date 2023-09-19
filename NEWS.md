# BayesRep 0.42.3
- fixed roxygen2 issue with package documentation
  (<https://github.com/r-lib/roxygen2/issues/1491>)

# BayesRep 0.42.2
- removed a test of `BFrlogOR` with `method = "hypergeo"` that fails on CRAN
  M1mac, I cannot reproduce the error (the test succeeds on CRAN's macOS builder
  and a coworkers M1 machine)

# BayesRep 0.42

- CRAN submission
- New functions:
  * equality of effect size Bayes factor `BFe`
  * generalized replication Bayes factor `BFr`, `BFrlogOR`, `BFrSMD`
  * sceptical Bayes factor `BFs`, `BFslogOR`, `BFsSMD`
  * effect size posterior distribution `repPosterior`
  * Bayes factor formatting `formatBF`
