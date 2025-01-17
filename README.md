
# Awesome R package development [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/IndrajeetPatil/awesome-r-pkgtools/)

A curated list of awesome tools to assist R 📦 development.

Note before:

-   Not all tools are available on [CRAN](https://cran.r-project.org/);
    some might be available only via GitHub or GitLab.
-   Only **tools** helpful for package development are included, and not
    other resources (like books, talks, presentations, etc.).
-   Tools which are part of publicly archived/retired GitHub
    repositories are not included.

# Contributing

If you wish to suggest any additional tools, please make a PR request or
raise an issue
[here](https://github.com/IndrajeetPatil/awesome-r-pkgtools).

Please note that the `awesome-r-pkgtools` project is released with a
[Contributor Code of
Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.

------------------------------------------------------------------------

<p align="center">
⚠️⚠️ <b>Note Before</b> ⚠️⚠️
</p>

If you are not using **the latest** release of
[pandoc](https://github.com/jgm/pandoc/releases), please change only the
`README.Rmd` document.

------------------------------------------------------------------------

# Swiss army knives 🛠

Tools useful across all stages of package development (some of these are
meta-packages and their component packages are also included in
respective sections for the sake of completeness).

-   [`{devtools}`](https://devtools.r-lib.org)

-   [`{usethis}`](https://usethis.r-lib.org)

-   [`{packager}`](https://cran.r-project.org/web/packages/packager/index.html)

-   [`{pacs}`](https://polkas.github.io/pacs/index.html)

# Package skeletons 💀

-   [`{pkgkitten}`](https://dirk.eddelbuettel.com/code/pkgkitten.html)
    (useful for creating new packages for R)

-   [`{rcompendium}`](https://frbcesab.github.io/rcompendium) (to make
    the creation of R package/research compendium easier)

-   [`{skeletor}`](https://github.com/nealrichardson/skeletor) (An R
    Package Skeleton Generator)

## Shiny

-   [`{golem}`](https://github.com/ThinkR-open/golem) (framework for
    building shiny applications)

-   [`{leprechaun}`](https://leprechaun.opifex.org/#/) (leaner framework
    for building shiny applications)

-   [`{rhino}`](https://appsilon.github.io/rhino/) (a framework to build
    high quality, enterprise-grade Shiny apps at speed)

-   [`{fusen}`](https://thinkr-open.github.io/fusen)
    (`{rmarkdown}`-based)

## Meta-packages

-   [`{pkgverse}`](https://pkgverse.mikewk.com) (for package meta-verse)

-   [`{metamakr}`](https://github.com/jdtrat/metamakr) (for package
    meta-verse)

# Naming things 🧸

-   [`{available}`](https://cran.r-project.org/web/packages/available/index.html)
    (to check if a package name is available to use)

-   [`{collidr}`](https://cran.r-project.org/web/packages/collidr/index.html)
    (to check for namespace collisions)

-   [`{changer}`](https://cran.r-project.org/web/packages/changer/index.html)
    (to change the name of an existing R package)

# Working with package components

-   [`{rprojroot}`](https://rprojroot.r-lib.org) (accessing files w.r.t.
    package root directory)

-   [`{desc}`](https://github.com/r-lib/desc#readme) (manipulating
    `DESCRIPTION` files)

-   [`{withr}`](https://withr.r-lib.org) (to manage package side effects
    by safely and temporarily modifying global states)

-   [`{pkgload}`](https://r-lib.github.io/pkgload) (to simulate the
    process of installing and loading a package)

-   [`{pkgbuild}`](https://cran.r-project.org/web/packages/pkgbuild/index.html)
    (to find tools needed to build packages)

# Package configuration

-   [`{config}`](https://rstudio.github.io/config/) (to manage
    environment specific configuration values)

# Package management tools

-   [`{pkgcache}`](https://cran.r-project.org/web/packages/pkgcache/index.html)
    (to cache ‘CRAN’-like metadata and packages)

# Documentation 📚

## Manual

-   [`{roxygen2}`](https://roxygen2.r-lib.org) (to generate R package
    documentation from inline R comments)

-   [`{Rd2roxygen}`](https://cran.r-project.org/web/packages/Rd2roxygen/index.html)
    (in case you inherit a project where documentation was not written
    using `{roxygen2}`)

-   [`{sinew}`](https://yonicd.github.io/sinew) (generate `{roxygen2}`
    skeletons)

-   [`{roclang}`](https://cran.r-project.org/web/packages/roclang)
    (helpers for diffusing content across function documentation)

-   [`{Rdpack}`](https://cran.r-project.org/web/packages/Rdpack/index.html)
    (for inserting references, figures, and evaluated examples in Rd
    docs)

-   [`{roxygen2md}`](https://roxygen2md.r-lib.org) (using Markdown
    syntax in package documentation)

-   [`{rd2list}`](https://github.com/coolbutuseless/rd2list) (converts
    Rd docs to a human-readable list)

-   [`roxygen2Comment`](https://github.com/csgillespie/roxygen2Comment)
    (Rstudio addin for adding and remove `{roxygen2}` comment)

## Math in package manual

-   [`{katex}`](https://docs.ropensci.org/katex) (to convert latex math
    expressions to HTML for use in package manual pages)

-   [`{mathjaxr}`](https://cran.r-project.org/web/packages/mathjaxr/index.html)
    (provides ‘MathJax’ and macros to enable its use within `Rd` files
    for rendering equations in the HTML help files)

## Vignettes

-   [`{knitr}`](https://yihui.org/knitr) (a general-purpose tool for
    dynamic report generation to be used as a vignette builder for R
    package vignettes)

-   [`{rmarkdown}`](https://rmarkdown.rstudio.com) (to convert R
    Markdown documents to a variety of formats)

-   [`{prettydoc}`](https://cran.rstudio.com/web/packages/prettydoc/index.html)
    (creates lightweight yet pretty vignettes)

-   [`{learnr}`](https://rstudio.github.io/learnr) (to turn any R
    Markdown document into an interactive tutorial)

## Website

-   [`{pkgdown}`](https://pkgdown.r-lib.org) (static website for package
    documentation)

-   [`{gitdown}`](https://github.com/ThinkR-open/gitdown) (software
    changes as a gitbook)

-   [`{altdoc}`](https://altdoc.etiennebacher.com) (use
    [docute](https://docute.org/) or [docsify](https://docsify.js.org/)
    to create a static website for package documentation)

## Translation

-   [`{potools}`](https://github.com/MichaelChirico/potools) (for
    translating messages and checking the “health” of the messaging
    corpus)

## Lifecycle

-   [`{lifecycle}`](https://lifecycle.r-lib.org/index.html) (to manage
    the life cycle of exported functions)

## Badges and stickers

-   [`{badger}`](https://cran.r-project.org/web/packages/badger/index.html)
    (query information and generate badges for using in `README` and
    `GitHub Pages`)

-   [`{hexSticker}`](https://cran.r-project.org/web/packages/hexSticker/index.html)
    (helper functions for creating reproducible hexagon sticker purely
    in R)

-   [`hexwall`](https://github.com/mitchelloharawild/hexwall) (to create
    a wall of hexstickers)

## Presentation

-   [`{xaringan}`](https://github.com/yihui/xaringan) (an R Markdown
    output format for `remark.js` slides)

## Book

-   [`{bookdown}`](https://pkgs.rstudio.com/bookdown) (authoring
    framework for books and technical documents with R Markdown)

## Change log and versioning

-   [`{fledge}`](https://cynkra.github.io/fledge/index.html)
    (streamlines the process of updating change logs and versioning R
    packages developed in git repositories)

-   [`{newsmd}`](https://cran.r-project.org/web/packages/newsmd/index.html)
    (utilities to add updates to the `NEWS.md` file)

# Documentation quality ✒️

-   [`{docreview}`](https://thisisnic.github.io/docreview) (to check
    quality of docs)

-   [`{spelling}`](https://docs.ropensci.org/spelling) (to check for
    spelling mistakes)

-   [`{gramr}`](https://github.com/jasdumas/gramr) (for grammar
    suggestions)

# Unit testing 🧪

## General

-   [`{testthat}`](https://testthat.r-lib.org) (a testing framework for
    R that is easy to learn and use; also provides snapshot testing)

-   [`{tinytest}`](https://cran.r-project.org/web/packages/tinytest/index.html)
    (zero-dependency unit testing framework that installs tests with the
    package)

-   [`{RUnit}`](https://cran.r-project.org/web/packages/RUnit/index.html)
    (a standard Unit Testing framework, with additional code inspection
    and report generation tools)

-   [`{testit}`](https://cran.rstudio.com/web/packages/testit/index.html)
    (a simple package for testing R packages)

-   [`{roxytest}`](https://github.com/mikldk/roxytest) (inline
    `{testthat}` tests with `{roxygen2}`)

-   [`{exampletestr}`](https://rorynolan.github.io/exampletestr) (tests
    based on package examples)

-   [`{unitizer}`](https://cran.r-project.org/web/packages/unitizer/index.html)
    (simplifies regression tests by comparing objects produced by test
    code with earlier versions of those same objects)

-   [`{r-hedgehog}`](https://github.com/hedgehogqa/r-hedgehog) (property
    based testing)

-   [`{autotest}`](https://docs.ropensci.org/autotest) (automatic
    mutation testing of R packages)

## Shiny applications

-   [`{shinytest}`](https://rstudio.github.io/shinytest) (testing Shiny
    apps)

-   [`{shinytest2}`](https://rstudio.github.io/shinytest2) (testing
    Shiny apps using a headless Chromium web browser)

## Web applications

-   [`{httptest}`](https://enpiar.com/r/httptest/) (a test environment
    for HTTP requests in R)

-   [`{httptest2}`](https://enpiar.com/httptest2/) (the same for
    `{httr2}` package)

## Visual regression testing

-   [`{vdiffr}`](https://vdiffr.r-lib.org) (visual regression testing)

## Mock testing

-   [`{mockthat}`](https://nbenn.github.io/mockthat) (function mocking
    for unit testing to third-party packages)

-   [`{mockr}`](https://krlmlr.github.io/mockr) (allows mocking
    functions in the package under test)

-   [`{testdown}`](https://github.com/ThinkR-open/testdown) (turn
    `{testthat}` results into a `{bookdown}` project)

## Helpers for testing frameworks

-   [`{testthis}`](https://cran.r-project.org/web/packages/testthis)
    (RStudio addins for working with files that contain tests)

-   [`{xpectr}`](https://github.com/LudvigOlsen/xpectr) (builds unit
    tests with the `{testthat}` package by providing tools for
    generating expectations)

# Code analysis 🗂⏱

## General

-   [`{codetools}`](https://cran.r-project.org/web/packages/codetools/index.html)
    (code analysis tools for R)

-   [`{goodpractice}`](http://mangothecat.github.io/goodpractice) (Swiss
    army knife for good practices)

-   [`{inteRgrate}`](https://github.com/jumpingrivers/inteRgrate)
    (provides an opinionated set of rules for R package development)

-   [`{pkgcheck}`](https://docs.ropensci.org/pkgcheck) (checks if
    package follows good practices recommended for packages in the
    [`rOpenSci`](https://ropensci.org/) ecosystem)

-   [`{rchk}`](https://github.com/kalibera/rchk) (provides several
    bug-finding tools that look for memory protection errors in C source
    code using R API)

-   [`{sourcetools}`](https://cran.r-project.org/web/packages/sourcetools/index.html)
    (tools for reading, tokenizing, and parsing R code)

## Code coverage

-   [`{covr}`](https://covr.r-lib.org) (computes code coverage)

-   [`{covrpage}`](https://yonicd.github.io/covrpage) (provides summary
    `README` of code coverage and corresponding tests)

## Lint detection

-   [`{lintr}`](https://github.com/jimhester/lintr) (static code
    analysis)

-   [`{roger}`](https://cran.r-project.org/web/packages/roger/index.html)
    (provides tools for grading the coding style and documentation of R
    scripts)

-   [`{cleanr}`](https://cran.r-project.org/web/packages/cleanr/index.html)
    (tests code for some of the most common code layout flaws)

## Code complexity

-   [`{cyclocomp}`](https://cran.r-project.org/web/packages/cyclocomp/index.html)
    (to index the complexity of a function)

## Code similarity

-   [`{dupree}`](https://github.com/russHyde/dupree) (identifies code
    blocks that have a high level of similarity within a set of R files)

-   [`{rscc}`](https://cran.r-project.org/web/packages/rscc/index.html)
    (provides source code similarity evaluation by variable/function
    names)

-   [`{SimilaR}`](https://cran.r-project.org/web/packages/SimilaR/index.html)
    (quantifies the similarity of the code-base of R functions by means
    of program dependence graphs)

## Lines of code

-   [`{cloc}`](https://github.com/hrbrmstr/cloc) (counts blank lines,
    comment lines, and physical lines of source code in source files)

# Code performance ⏱️

## Benchmarking

-   [`{bench}`](https://bench.r-lib.org/) (provides high precision
    benchmarks for R expressions)

-   [`{microbenchmark}`](https://cran.r-project.org/web/packages/microbenchmark/index.html)
    (provides infrastructure to accurately measure and compare the
    execution time of R expressions)

-   [`{touchstone}`](https://lorenzwalthert.github.io/touchstone)
    (benchmarking pull requests)

## Profiling

-   [`{profvis}`](https://cran.r-project.org/web/packages/profvis/index.html)
    (to profile and visualize profiling data)

-   [`{proffer}`](https://r-prof.github.io/proffer/) (to create
    friendlier, faster visualizations for profiling data)

-   [`{jointprof}`](https://r-prof.github.io/jointprof/) (to profile
    packages with native code in C, C++, Fortran, etc.)

# Formatting 🧽

-   [`{styler}`](https://styler.r-lib.org) (to format code according to
    a style guide)

-   [`{stylermd}`](https://github.com/lorenzwalthert/stylermd) (to
    format text in Markdown documents)

-   [`{formatR}`](https://yihui.org/formatr) (to format R source code)

-   [`AlignAssign`](https://github.com/seasmith/AlignAssign) (RStudio
    addin that aligns the assignment operators within a highlighted
    area)

-   [`{snakecase}`](https://tazinho.github.io/snakecase/) (helpful for
    having consistent case while naming objects in the package)

# Dependencies ⚖️

-   [`{pkgdepends}`](https://cran.r-project.org/web/packages/pkgdepends/index.html)
    (to find recursive dependencies of from various sources)

-   [`{deepdep}`](https://cran.r-project.org/web/packages/deepdep/index.html)
    (to visualize and explore package dependencies)

-   [`{itdepends}`](https://github.com/r-lib/itdepends) (to assess
    usage, measure weights, visualize proportions, and assist removal of
    dependencies)

-   [`{DependenciesGraphs}`](https://github.com/datastorm-open/DependenciesGraphs)
    (to visualize package dependencies)

-   [`{pkgnet}`](https://uptake.github.io/pkgnet/index.html) (to build a
    graph representation of a package and its dependencies)

-   [`{functiondepends}`](https://cran.r-project.org/web/packages/functiondepends)
    (to find functions in an unstructured directory and explore their
    dependencies)

-   [`{pkgndep}`](https://cran.r-project.org/web/packages/pkgndep)
    (checks the heaviness of the packages used)

-   [`{oysteR}`](https://sonatype-nexus-community.github.io/oysteR) (to
    secure package against insecure dependencies)

-   [`{attachment}`](https://github.com/ThinkR-open/attachment) (to deal
    with package dependencies during package development)

# CRAN checks, submission, and status 📬

-   [`{rcmdcheck}`](https://r-lib.github.io/rcmdcheck) (to run
    `R CMD check` form R programmatically)

-   [`{rhub}`](https://cran.r-project.org/web/packages/rhub/index.html)
    (to run `R CMD check` on CRAN architectures)

-   [`{checkhelper}`](https://thinkr-open.github.io/checkhelper) (to
    help avoid problems with CRAN submissions)

-   [`{foghorn}`](https://cran.r-project.org/web/packages/foghorn/index.html)
    (to check for results and submission portal status)

-   [`{urlchecker}`](https://github.com/r-lib/urlchecker) (to checks for
    URL rot)

# Usage 🙈

-   [`{cranlogs}`](https://r-hub.github.io/cranlogs) (for computing CRAN
    download counts)

-   [`{packageRank}`](https://cran.r-project.org/web/packages/packageRank/index.html)
    (for visualizing CRAN download counts)

-   [`{dlstats}`](https://guangchuangyu.github.io/dlstats/) (provides
    download statistics for packages)

# CI/CD 📟

CI/CD: continuous integration and either continuous delivery or
continuous deployment

-   [`actions`](https://github.com/r-lib/actions) (for [GitHub
    Actions](https://github.com/features/actions))

-   [`r-appveyor`](https://github.com/krlmlr/r-appveyor) (for
    [AppVeyor](https://www.appveyor.com/))

-   [`{tic}`](https://docs.ropensci.org/tic) (for [Circle
    CI](https://circleci.com/) and [GitHub
    Actions](https://github.com/features/actions))

-   [`{jenkins}`](https://docs.ropensci.org/jenkins) (for [Jenkins
    CI](https://www.jenkins.io/))

-   [`{cronR}`](https://github.com/bnosac/cronR) (to schedule R
    scripts/processes with the cron scheduler)

# Security/Privacy 👮

-   [`{digest}`](https://cran.r-project.org/web/packages/digest/index.html)
    (for the creation of hash digests of arbitrary R objects)

-   [`{hash}`](https://cran.r-project.org/web/packages/hash/index.html)
    (implements a data structure similar to hashes in Perl and
    dictionaries in Python but with a purposefully R flavor)

-   [`{gpg}`](https://cran.r-project.org/web/packages/gpg/index.html)
    (GNU privacy guard for R)

# Build systems

-   [`{fakemake}`](https://cran.r-project.org/web/packages/fakemake/index.html)
    (to mock Unix Make build system in case it is unavailable)

# Validation frameworks

-   [`{valtools}`](https://phuse-org.github.io/valtools/index.html) (in
    clinical research and drug development)

# Debugging 🔭

-   [`{debugme}`](https://github.com/r-lib/debugme) (provides helpers to
    specify debug messages as special string constants, and control
    debugging of packages via environment variables)

-   [`{debugr}`](https://cran.r-project.org/web/packages/debugr) (tools
    to print out the value of R objects/expressions while running an R
    script)

-   [`{winch}`](https://r-prof.github.io/winch/) (provides stack traces
    for call chains that cross between R and C/C++ function calls)

-   [`{flow}`](https://moodymudskipper.github.io/flow/) (to visualize as
    flow diagrams the logic of functions, expressions, or scripts, which
    can ease debugging)

# Input validation 🔬

-   [`{checkmate}`](https://mllg.github.io/checkmate) (fast and
    versatile argument checks)

-   [`{assertthat}`](https://cran.r-project.org/web/packages/assertthat/index.html)
    (to declare the pre and post conditions that you code should satisfy
    and to produce friendly error messages)

-   [`{assertive}`](https://www.r-pkg.org/pkg/assertive) (provides
    readable check functions to ensure code integrity)

-   [`{pkgcond}`](https://github.com/RDocTaskForce/pkgcond) (better
    error messages for package users)

-   [`{dreamerr}`](https://github.com/lrberge/dreamerr) (a simple and
    intuitive, yet powerful and flexible, way to check the arguments
    passed to a function and to offer informative error messages)

# Package metadata 🖨

-   [`{codemetar}`](https://docs.ropensci.org/codemetar) (provides
    utilities to generate, parse, and modify `codemeta.jsonld` files
    automatically for R packages)

-   [`{codemeta}`](https://docs.ropensci.org/codemeta) (a leaner version
    of `{codemetar}`)

-   [`{cffr}`](https://docs.ropensci.org/cffr) (provides utilities to
    generate, parse, modify and validate `CITATION.cff` files
    automatically for R packages)

-   [`{pkgapi}`](https://github.com/r-lib/pkgapi) (to create the map of
    function calls in a package)

-   [`{packagemetrics}`](https://github.com/sfirke/packagemetrics) (for
    comparing among packages)

-   [`{devtoolbox}`](https://martinctc.github.io/devtoolbox/index.html)
    (to create a summary report for R package and to extract dependency
    statistics in a tidy data frame)

-   [`{pkgattrs}`](https://rich-iannone.github.io/pkgattrs) (useful for
    getting information on the contents of any R package)

-   [`{foreman}`](https://github.com/yonicd/foreman) (for unpacking,
    interrogating and subsetting R packages)

-   [`{sessioninfo}`](https://r-lib.github.io/sessioninfo/) (to include
    R session information)

# Reverse dependency checks 📡⚰️

-   [`{revdepcheck}`](https://r-lib.github.io/revdepcheck) (for
    automated, isolated, reverse dependency checking)

-   [`{xfun}`](https://yihui.org/xfun) (specifically,
    `xfun::rev_check()`)

# Gratitude 🙏💌

To thank the contributors or maintainers of packages you rely on.

-   [`{thankr}`](https://cran.r-project.org/web/packages/thankr/index.html)
    (to find out who maintains the packages you are using)

-   [`{allcontributors}`](https://docs.ropensci.org/allcontributors) (to
    help acknowledge all contributions)

# Docker container 🛍

-   [`{containerit}`](https://o2r.info/containerit) (to package R
    script/session/workspace and all dependencies as a `Docker`
    container by generating a suitable `Dockerfile`)

-   [`{usethat}`](https://tidylab.github.io/usethat) (to automate
    analytic project setup tasks)

# Integration with other languages 🔗

## C++

-   [`{Rcpp}`](https://cran.r-project.org/web/packages/Rcpp/index.html)

-   [`{cpp11}`](https://cpp11.r-lib.org/index.html)

-   [`{memtools}`](https://memtools.r-lib.org/) (to solve memory leaks)

## Python

-   [`{reticulate}`](https://cran.r-project.org/web/packages/reticulate/index.html)

## Rust

-   [`{cargo}`](https://cran.r-project.org/web/packages/cargo/index.html)

-   [`{hellorust}`](https://github.com/r-rust/hellorust)

## .NET Framework

-   [`{rClr}`](https://github.com/rdotnet/rClr)

## JavaScript/HTML/CSS

-   [`{htmltools}`](https://rstudio.github.io/htmltools/reference/index.html#section-html-dependencies)
-   [`{packer}`](https://packer.john-coene.com)

## Julia

-   [`{JuliaCall}`](https://non-contradiction.github.io/JuliaCall/index.html)

# Upkeep 🧹

-   [`{TODOr}`](https://github.com/dokato/todor) (RStudio addin to list
    things that you need to do or change)

# Sundry 🗒

-   [`{prefixer}`](https://github.com/dreamRs/prefixer) (prefix function
    with their namespace )

-   [`{rstudioapi}`](https://rstudio.github.io/rstudioapi/)(to
    conditionally access the RStudio API from CRAN packages)

-   [`{gitignore}`](https://cran.r-project.org/web/packages/gitignore/index.html)
    (to fetch gitignore templates)

-   [`{precommit}`](https://lorenzwalthert.github.io/precommit)
    (pre-commit hooks)

-   [`{DIZutils}`](https://cran.r-project.org/web/packages/DIZutils/index.html)
    (helpers for packages dealing with database connections)

# Code of Conduct

Please note that the awesome-r-pkgtools project is released with a
[Contributor Code of
Conduct](https://contributor-covenant.org/version/2/1/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.
