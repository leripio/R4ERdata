# R4ER2data

[![Download Release](https://img.shields.io/badge/Download-v1.0.0-blue)](https://github.com/leripio/R4ER2data/releases/latest)
[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

Dataset package to support the exercises from the book *R for Economic Research*.

---

## Installation

You can install the package in two ways:

### 1. From GitHub Releases (pre-compiled)

Download and install the latest stable version:

```r
install.packages(
  "https://github.com/leripio/R4ER2data/releases/download/v1.0.0/R4ER2data_1.0.0.tar.gz",
  repos = NULL,
  type = "source"
)
```

### 2. From source via GitHub (requires devtools)

```r
# Install devtools if you haven't already
install.packages("devtools")

# Install the development version from GitHub
devtools::install_github("leripio/R4ER2data")
```

---

## Usage

Once installed, you can load the package and access the datasets:

```r
library(R4ER2data)

# Example: list available datasets
data(package = "R4ER2data")
```

---

## License

This package is licensed under the MIT License.
