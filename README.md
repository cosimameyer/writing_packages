# Big things come in small packages - Tips and tricks for your own R package

![](https://cosimameyer.rbind.io/talk/r-package/featured%2022.41.41_hu169a416274258688cd88166c5eafa828_701812_720x0_resize_lanczos_2.png)

📍 CorrelCon 2021

## About the talk

R is a great resource for data management, statistics, analysis, and visualization — and it becomes better every day. This is to a large part because of the active community that continuously creates and builds extensions for the R world. Dur- ing the talk, I will provide you with tips and tricks for contributing to this world by writing packages. If you want to get a quick introduction before the talk, [here is a hands-on tutorial](https://www.mzes.uni-mannheim.de/socialsciencedatalab/article/r-package/) on how to write your first R package.

## Material

You can access the material here:

| [Slides](hhttps://cosimameyer.com/slides/correlcon2021/talk.html#1) | [Package example](https://github.com/cosimameyer/writing_packages/tree/main/correlcalc) | 
|--------|----------|

## Overview repository

This repository contains:

```
├── correlcalc
│   ├── DESCRIPTION
│   ├── NAMESPACE
│   ├── R
│   │   └── make_sum.R
│   ├── correlcalc.Rproj
│   └── man
│       └── make_sum.Rd
└── writing_packages.Rproj
```

## More resources

- [Full working package example (`overviewR`)](https://github.com/cosimameyer/overviewR)
- [How to write your own R package and publish it on CRAN (Cosima Meyer and Dennis Hammerschmidt)](https://www.mzes.uni-mannheim.de/socialsciencedatalab/article/r-package/)
- [R Packages (Hadley Wickham)](http://r-pkgs.had.co.nz/)
- [How to develop good R packages (for open science) (Maëlle Salmon)](https://masalmon.eu/2017/12/11/goodrpackages/)
- [devtools Cheat Sheet](https://rawgit.com/rstudio/cheatsheets/master/package-development.pdf)
- [Writing an R package from scratch (Hilary Parker)](https://hilaryparker.com/2014/04/29/writing-an-r-package-from-scratch/)
- [Your first R package in 1 hour (Shannon Pileggi)](https://www.pipinghotdata.com/talks/2020-10-25-your-first-r-package-in-1-hour/)
- [R package primer (Karl Broman)](https://kbroman.org/pkg_primer/)
- [Checklist for R Package (Re-)Submissions on CRAN (Saskia Otto)](https://www.marinedatascience.co/blog/2020/01/09/checklist-for-r-package-re-submissions-on-cran/)
- [Continuous integration with GitHub Actions (Dean Attali )](https://deanattali.com/blog/migrating-travis-to-github/)
