# Assignment 2: Spatial Analysis and Interpolation in R

## Overview

This assignment explores spatial statistical methods to analyse geographic patterns and make predictions using R. It focuses on two applications:

1. **COVID-19 Case Distribution in Wuhan:** Mapped early COVID-19 cases surrounding the Huanan Market and used kernel density estimation (KDE) to identify areas of high case concentration. Applied an Inhomogeneous Poisson Point Process (IPPP) model to examine spatial patterns while accounting for population density.

2. **Soil pH Analysis in Indiana:** Analysed soil pH measurements across Indiana counties to assess agricultural suitability. Categorised soil samples by depth, fitted variogram models and applied block kriging to estimate soil pH across counties for three soil sublayers.

## Skills Demonstrated

- Spatial data cleaning, filtering and coordinate transformations
- Geographic mapping and visualisation
- Integration of OpenStreetMap geographic data
- Kernel density estimation and spatial point process modelling
- Incorporating population density as a spatial covariate
- Variogram analysis and spatial autocorrelation
- Block kriging and spatial interpolation
- Classification and visualisation of geographic areas based on predicted values

## Technologies

**R** | `sf` | `spatstat` | `gstat` | `ggplot2` | `tmap` | `terra` | `osmdata` | `dplyr` | Quarto

*Coursework completed as part of DATA*6500, University of Guelph.*
