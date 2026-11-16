# TESS

Simulation of reconstructed phylogenetic trees under tree-wide time-heterogeneous birth-death processes, including mass-extinction events, and estimation of diversification parameters under the same model.

Compatibility updates by Renova.

Version 2.1.2.9001: documentation and metadata only: help-page links to `read.tree` and `ape` are anchored to the ape package, the plot-type lists in three plotting help pages use valid `\itemize` syntax, and the DESCRIPTION gains `Authors@R` and drops the stale `Date`. Package functions and C++ code are unchanged.

## Install

```r
install.packages("TESS", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

See the [R-universe package page](https://renova-r.r-universe.dev/TESS) for builds and installation. This release is tagged on GitHub as `renova-2.1.2.9001`:

```r
remotes::install_github("renova-r/TESS@renova-2.1.2.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

TESS is by Sebastian Hoehna (maintainer) and Michael R. May; the original CRAN package is at <https://CRAN.R-project.org/package=TESS>. License: GPL-3; see [COPYING](COPYING).

### Metadata compatibility

Updated CITATION constructors while preserving the citation text and bibliographic fields.
