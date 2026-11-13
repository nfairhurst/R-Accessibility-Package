
# Stataccess Package

### An R Package for Accessible Statistical Visualizations

`stataccess` is an R package designed to make statistical graphics more accessible to individuals with visual impairments, including blindness, low vision, and color-vision deficiencies.

This package is being developed as part of a Statistical Programming course.

## Features

The package will include two main functions:

### `describe_plot()`
- Generates plain-language descriptions of ggplot2 visualizations.
- Provides basic descriptive statistics.
- Produces text intended for use with screen readers and Braille displays.

### `accessible_plot()`
- Improves graph readability for individuals with low vision.
- Provides colorblind-friendly visualization options.
- Allows users to customize accessibility settings.

## Installation

The package is currently under development.

Once published on GitHub, it can be installed using:

```r
install.packages("remotes")
remotes::install_github("USERNAME/stataccess")
```

## Technologies

- R
- ggplot2
- roxygen2
- testthat

## Future Development

Future improvements may include support for additional graph types, enhanced screen-reader compatibility, and more accessibility options for statistical analysis.

## Authors

- Nathan Fairhurst
- Sven Engelbrecht

## Project Status

**Version 0.1.0 — Under Development**
