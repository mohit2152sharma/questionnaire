# questionnaire

<!-- badges: start -->
[![CodeFactor](https://www.codefactor.io/repository/github/mohit2152sharma/questionnaire/badge)](https://www.codefactor.io/repository/github/mohit2152sharma/questionnaire)
[![CircleCI](https://circleci.com/gh/mohit2152sharma/questionnaire/tree/main.svg?style=svg)](https://circleci.com/gh/mohit2152sharma/questionnaire/tree/main)
[![Project Status: WIP – Initial development is in progress, but there has not yet been a stable, usable release suitable for the public.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip) 
[![Licence](https://img.shields.io/badge/Licence-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![CRAN\_Status\_Badge](https://www.r-pkg.org/badges/version/questionnaire)](https://cran.r-project.org/package=questionnaire)

<!-- 
[![codecov](https://codecov.io/gh/RMHogervorst/badgecreatr/branch/master/graph/badge.svg)](https://codecov.io/gh/RMHogervorst/badgecreatr)  -->

<!-- [![minimal R version](https://img.shields.io/badge/R%3E%3D-3.2.4-6666ff.svg)](https://cran.r-project.org/)  -->

<!-- [![packageversion](https://img.shields.io/badge/Package%20version-0.1.0-orange.svg?style=flat-square)](commits/develop)  -->

<!-- TODO: #3 Adding badges as comment which shall be added later -->

<!-- badges: end -->

## Overview

`questionnaire` is a R package with questions about R programming language. 


## Proposed functonality
- should have `start_quiz()` which will render a quiz on a localhost using shiny framework
- `start_quiz()` should allow how many questions should be there in the quiz. Default can be 5
- For reference, see: [LearnR](https://rstudio.github.io/learnr/) package.
- For starters, the package will come with default set of questions. The quiz will be created by selecting questions from this default set at random.
- The package should have a template that will allow users to submit questions with pull requests
- A workflow to automatically integrate user submitted questions into the package