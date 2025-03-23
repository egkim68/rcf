# Region-based Scatterplot Analysis (RCF)

This repository implements the Region-based Comparison Framework (RCF), a method for partitioning scatterplots into interpretable regions using both absolute and relative modes. It includes visualization tools, density calculations, and transformation metrics such as net flow and redistribution index to measure structural changes after normalization.

## Features
- Partition scatterplots into k×k grids (e.g., 4×4)
- Supports both raw (absolute) and normalized (relative) partitioning
- Visualizes labeled regions on scatterplots
- Calculates density and transformation metrics:
  - Net Flow
  - Relative Change Ratio
  - Redistribution Index
- Includes examples using the Iris and AirQuality datasets from base R

## Requirements
- R ≥ 4.0
- Packages: `dplyr`, `ggplot2`, `tidyr`, `patchwork`


