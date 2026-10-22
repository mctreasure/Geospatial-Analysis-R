# Geospatial-Analysis-R
Geospatial analysis, visualisation and spatial modelling projects completed in R.

# Geospatial Analysis in R

## Overview

This repository contains projects completed as part of the graduate-level Geospatial Analysis course (DATA*6500) at the University of Guelph during my Master of Data Science.

The assignments explore techniques for working with geographic data, including spatial data processing, visualisation, statistical modelling and predictive analysis using R.

## Projects

### Assignment 1: Geospatial Analysis and Spatial Modelling

Explored three applications of geospatial analysis:

- **Ottawa Starbucks Distribution:** Used spatial joins and population data to analyse the geographic distribution of Starbucks locations across Ottawa.
- **Zion National Park:** Combined OpenStreetMap trail data with elevation rasters to map hiking routes and analyse elevation changes.
- **Landslide Prediction:** Applied elastic net logistic regression and spatial cross-validation to investigate relationships between terrain characteristics and landslide occurrence.

**Key techniques:** Spatial joins, coordinate transformations, raster processing, elevation analysis, predictive modelling and spatial cross-validation.

### Assignment 2: Spatial Statistics and Kriging

Applied spatial statistical methods to two geographic datasets:

- **COVID-19 Cases in Wuhan:** Used kernel density estimation and an Inhomogeneous Poisson Point Process model to examine the spatial distribution of early COVID-19 cases while accounting for population density.
- **Soil pH in Indiana:** Used variogram analysis and block kriging to estimate soil pH across counties and assess agricultural suitability at different soil depths.

**Key techniques:** Kernel density estimation, point process modelling, spatial autocorrelation, variogram fitting and spatial interpolation.

## Tools and Technologies

**Language:** R

**Key packages:** `sf`, `terra`, `ggplot2`, `dplyr`, `osmdata`, `spatstat`, `gstat`, `mlr3`

**Other tools:** Quarto, OpenStreetMap

## Repository Structure

Each assignment is organised into its own folder containing the original R/Quarto code and a short README describing the analysis and techniques used.

The code is provided to demonstrate my approach to spatial analysis and statistical modelling. Supporting datasets are not included, so the assignments are not intended to run independently.
