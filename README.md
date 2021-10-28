
# Awesome R package development [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/IndrajeetPatil/awesome-r-pkgtools/)

A curated list of awesome tools for R package development. Inspired by
awesome-… stuff.

N.B.:

-   Not all tools are available on CRAN; some might be available only
    via GitHub or GitLab.
-   Only tools helpful for package development are included, and not
    other resources like books, talks, presentations, etc.

If you wish to suggest any additional tools, please make a PR request
here: <https://github.com/IndrajeetPatil/awesome-r-pkgtools>

Please note that the `awesome-r-pkgtools` project is released with a
[Contributor Code of
Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.

# Swiss Army knives

These package contain tools that are useful across all stages of package
development, from the beginning to the end.

-   `{devtools}`: <https://devtools.r-lib.org/>

-   `{usethis}`: <https://usethis.r-lib.org/>

# Package skeletons

-   `{pkgkitten}`: <https://dirk.eddelbuettel.com/code/pkgkitten.html>

# Documentation

## Manual

-   `{roxygen2}`: <https://roxygen2.r-lib.org/>

-   `{Rd2roxygen}`:
    <https://cran.r-project.org/web/packages/Rd2roxygen/index.html> (in
    case you inherit a project where documentation was not written using
    `{roxygen2}`)

-   `{sinew}`: <https://yonicd.github.io/sinew/> (generate `{roxygen2}`
    skeletons)

-   `{roclang}`: <https://cran.r-project.org/web/packages/roclang/>
    (helpers for diffusing of content across function documentation)

-   `{roxygen2md}`: <https://roxygen2md.r-lib.org/> (using Markdown
    syntax in package documentation)

-   `roxygen2Comment`: <https://github.com/csgillespie/roxygen2Comment>
    (An Rstudio addin for adding and remove `{roxygen2}` comment)

## Vignettes

-   `{knitr}`: <https://yihui.org/knitr/>

-   `{rmarkdown}`: <https://rmarkdown.rstudio.com/>

## Website

-   `{pkgdown}`: <https://pkgdown.r-lib.org/>

# Unit testing

-   `{testthat}`: <https://testthat.r-lib.org/>

-   `{tinytest}`:
    <https://cran.r-project.org/web/packages/tinytest/index.html>

-   `{vdiffr}`: <https://vdiffr.r-lib.org/> (visual regression testing)

# Code coverage:

-   `{covr}`: <https://covr.r-lib.org/>

-   `{covrpage}`: <https://yonicd.github.io/covrpage/> ( summary
    `README` of code coverage)

# CI/CD

> “In software engineering, CI/CD or CICD is the combined practices of
> continuous integration and either continuous delivery or continuous
> deployment.”

-   `actions`: <https://github.com/r-lib/actions> (for [GitHub
    Actions](https://github.com/features/actions))

-   `r-appveyor`: <https://github.com/krlmlr/r-appveyor> (for
    [AppVeyor](https://www.appveyor.com/))

# Good practices

Not needed, but a **really good idea** to follow as many of them as you
can.

## General

-   `{goodpractice}`: <http://mangothecat.github.io/goodpractice/>
    (Swiss army knife for good practices)

## Formatting R code

-   `{styler}`: <https://styler.r-lib.org/> (especially relevant if you
    follow tidyverse style guide)

-   `{formatR}`: <https://yihui.org/formatr/>

## Detecting lints

-   `{lintr}`: <https://github.com/jimhester/lintr> (static code
    analysis)

## Spellcheck

-   `{spelling}`: <https://docs.ropensci.org/spelling/>

## Link rot

-   `{urlchecker}`: <https://github.com/r-lib/urlchecker> (Run CRAN URL
    checks)

## Package metadata

-   `{codemetar}`: <https://docs.ropensci.org/codemetar/>

-   `{pkgapi}`: <https://github.com/r-lib/pkgapi>

# Reverse dependency checks

-   `{revdepcheck}`: <https://r-lib.github.io/revdepcheck/>

# Using C++

# Creating package universe

-   `{pkgverse}`: <https://pkgverse.mikewk.com/>

# TO-DOs

Tools to keep track of things that you need to do in the future
releases.

-   `{TODOr}`: <https://github.com/dokato/todor> (RStudio add-in)
