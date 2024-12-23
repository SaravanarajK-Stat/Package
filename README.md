# creativePackage

[![Build Status](https://travis-ci.com/<username>/creativePackage.svg?branch=main)](https://travis-ci.com/<username>/creativePackage)

This package includes a creative function to generate a random dataset and perform exploratory data analysis.

## Installation

```r
# Install directly from GitHub (once uploaded)
# devtools::install_github("<username>/creativePackage")
```

## Example

```r
library(creativePackage)
result <- generate_random_data(10, 3)
print(result$data)
print(result$summary)
```
