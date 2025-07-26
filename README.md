# Sectoral Analysis of Germany's 2024 Economic Downturn

![Germany GDP Analysis](https://via.placeholder.com/800x400.png?text=Germany+Economic+Trends) <!-- Add actual economic visualization here -->

## Overview
This project analyzes sectoral contributions to Germany's 2024 economic contraction using Eurostat data. It identifies key sectors driving the downturn through time-series visualization and regression analysis, providing insights for economic policy responses.

## Key Findings
- **Manufacturing (C)** and **Trade/Transport (G-I)** were primary drivers of GDP contraction
- **Construction (F)** exerted significant negative pressure
- 67% of GDP fluctuation explained by sectoral GVA changes
- Manufacturing sector impact: -0.82pp GDP (p<0.001)

[![R Version](https://img.shields.io/badge/R-4.3.2-blue)]()
[![License](https://img.shields.io/badge/License-MIT-green)]()

## Methodology
```mermaid
graph LR
A[Eurostat Data] --> B[Data Extraction]
B --> C[Data Cleaning]
C --> D[Merging GDP & GVA]
D --> E[Time-Series Visualization]
E --> F[Regression Modeling]
F --> G[Policy Insights]
