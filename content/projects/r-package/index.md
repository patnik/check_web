---
title: "extRatum"
date: 2021-11-01T10:49:34+01:00
draft: false
weight: 100
---

An R package that calculates summary indices for built environment characteristics.

## Overview

`extRatum` is a package used to provide summary statistics of local geospatial features within a given geographic area. It does so by calculating the area covered by a target geospatial feature (i.e. buildings, parks, lakes, etc.). The geospatial features can be of any type of geospatial data, including point, polygon or line data.
For examples of `extRatum` functionalities follow this [link](https://github.com/patnik/extRatum_examples) and for the package website this [link](https://patnik.github.io/extRatum/index.html).


## Installation
The easiest way to get extRatum is to install it from CRAN:

```
install.packages("extRatum")
```


### Development version

To get a bug fix or to use a feature from the development version, you can install 
the development version of extRatum from GitHub.

```
# install.packages("devtools")
devtools::install_github("patnik/extRatum")
```
## Citation

To extract `extRatum` citation, type the following code.

```
citation('extRatum')
```

```

To cite package 'extRatum' in publications use:

 Nikos Patias and Francisco Rowe (2021). extRatum: Summary Statistics
 for Geospatial Features. R package version 1.0.4.
 https://CRAN.R-project.org/package=extRatum
 
 A BibTeX entry for LaTeX users is
 @Manual{,
 title = {extRatum: Summary Statistics for Geospatial Features},
 author = {Nikos Patias and Francisco Rowe},
 year = {2021},
 note = {R package version 1.0.4},
 url = {https://CRAN.R-project.org/package=extRatum},
 }
```

