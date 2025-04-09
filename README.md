# Peatland Climate Boundaries

This repository contains code and analysis for investigating the climate boundaries of peatland ecosystems.

## Project Overview

This project analyzes the relationship between peatland ecosystems and climate variables, with a focus on:
- Mean Annual Temperature (MAT)
- Annual Precipitation (AP)
- Precipitation Seasonality (PS)

## Repository Structure

```
├── data/           # Data directory (not tracked in git)
├── R/              # R scripts
├── docs/           # Documentation
├── output/         # Generated files
└── figures/        # Generated figures
```

## Getting Started

### Prerequisites

This project requires R and the following R packages:
- car
- dplyr
- glmnet
- caret
- readr
- patchwork
- randomForest
- ranger
- ggcorrplot
- ppcor
- nortest
- MuMIn
- smotefamily
- plotly
- ggeffects
- ROSE
- MASS
- gridExtra
- tidyr
- DHARMa
- kSamples
- shapviz
- recipes
- themis
- extrafont

### Installation

```R
# Install required packages
packages <- c('car', 'dplyr', 'glmnet', 'caret', 'readr', 'patchwork', 'randomForest')
install.packages(packages)
```

## Usage

The main analysis script is `R/Peatland_Climate_Niche.R`. This script performs:
1. Data preprocessing and cleaning
2. Climate variable analysis
3. Statistical modeling
4. Visualization of results

## Contributing

Contributions are welcome. Please open an issue first to discuss what you would like to change.

## Authors

* **Enahu Tahitu**

## License

This project is licensed under the MIT License - see the LICENSE file for details

## Acknowledgments

* WATERLands Project Team
* Contributors and Reviewers