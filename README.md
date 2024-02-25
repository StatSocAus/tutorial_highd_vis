# SSA SCV Tutorial: Visualising High-dimensional Data with R 

<img src="SCV3.png" align="right" width="150" />

Website: [https://StatSocAus.github.io/tutorial_highd_vis](https://StatSocAus.github.io/tutorial_highd_vis)

This is for scientists and data science practitioners who regularly work with high-dimensional data and are interested in learning how to better visualise this data. 

**Presenter**: Dianne Cook is Professor of Statistics at Monash University in Melbourne, Australia.  She is a world leader in data visualisation, especially the visualisation of high-dimensional data using tours with low-dimensional projections, and projection pursuit.  She also works on bridging the gap between exploratory graphics and statistical inference.  Di is a Fellow of the American Statistical Association, past editor of the Journal of Computational and Graphical Statistics, and the R Journal, elected Ordinary Member of the R Foundation, and elected member of the International Statistical Institute.

## Structure of tutorial

- Review of common practice, and introduction to using tour methods
- Application to supervised and unsupervised methods.

Background: Participants should have a good working knowledge of R, and some background in multivariate statistical methods and/or data mining techniques.

## Course Schedule

| time | topic |
|------|-------|
|1:00-1:20|	Introduction: What is high-dimensional data, why visualise and overview of methods| 
|1:20-1:45|	Basics of linear projections, and recognising high-d structure|
|1:45-2:30|	Effectively reducing your data dimension, in association with non-linear dimension reduction|
|2:30-3:00|	BREAK|
|3:00-3:45|	Understanding clusters in data using visualisation|
|3:45-4:30|	Building better classification models with visual input|

[Session 1 Slides (COMING SOON)]()

[Session 2 Slides (COMING SOON)]()

[Zip file of materials (COMING SOON)]()

## Getting started

1. You should have a reasonably up to date version of R and R Studio, eg RStudio RStudio 2023.06.2 +561 and R version 4.3.1 (2023-06-16). Install the following packages, and their dependencies.

```
install.packages(c("ggplot2", "tourr", "mulgar", "geozoo", "langevitour", "detourr", "MASS", "randomForest", "aweSOM", "cxhull", "mclust", "Rtsne", "e1071", "classifly", "plotly", "readr", "tidyr", "dplyr", "stringr", "colorspace",  "patchwork"), dependencies=c("Depends", "Imports"))
```

2. Download the [Zip file of materials](https://statsocaus.github.io/tutorial_highd_vis/tutorial.zip) to your laptop, and unzip it. 

3. Download just the R scripts, [slides1.R](https://statsocaus.github.io/tutorial_highd_vis/slides1.R), [slides2.R](https://statsocaus.github.io/tutorial_highd_vis/slides2.R)

4. Open your RStudio be clicking on `tutorial.Rproj`. 

GitHub repo with all materials is 
[https://statsocaus.github.io/tutorial_highd_vis/](https://statsocaus.github.io/tutorial_highd_vis/).

