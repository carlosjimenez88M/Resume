# Daniel Jiménez Resume

In this repository you can find two versions of my CV 

* [Spanish Version]() in Markdown format

* [English Version]() in LaTeX

## Vitae in Rmarkdown

# vitae <img src="https://i.imgur.com/PeFoXDy.png" align="right" />

*/ˈviːteɪ/*

[![CRAN
status](https://www.r-pkg.org/badges/version/vitae)](https://cran.r-project.org/package=vitae)
[![Travis build
status](https://travis-ci.org/mitchelloharawild/vitae.svg?branch=master)](https://travis-ci.org/mitchelloharawild/vitae)

## Description 

The vitae package makes creating and maintaining a Résumé or CV with R Markdown simple[^1]. With similar structure (syntax) that LaTex(https://es.overleaf.com/learn/latex/Free_online_introduction_to_LaTeX_(part_1)) Markdown in R allows :


* Automatically get your work experience from the web
* Intelligence tools in CV (hpr)
* Filter Keywords relevants
* Create multiples versions: Pdf, Word, Html.



## Installation


### Alternative One


``` r
install.packages('vitae')
```


### Alternative Two

``` r
# install.packages("devtools")
devtools::install_github("mitchelloharawild/vitae")
```


This package requires LaTeX to be installed on your computer. If you’re
encountering issues, please check that LaTeX is installed. The [tinytex
package](https://github.com/yihui/tinytex) makes it easy to setup LaTeX
within R[^2]:

``` r
install.packages('tinytex')
tinytex::install_tinytex()
```






[^1]:https://cran.r-project.org/web/packages/vitae/vignettes/vitae.html
[^2]: https://github.com/carlosjimenez88M/vitae/edit/master/README.md

