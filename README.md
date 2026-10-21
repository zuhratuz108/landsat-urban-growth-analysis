# Urban Expansion Analysis in Bangladesh's City Corporations (2020–2025)

A geospatial research project examining urban expansion across 12 city corporations in Bangladesh using satellite-derived land-use/land-cover (LULC) data, spatial predictors, and statistical and machine-learning models.

## Research Overview

Urban expansion transforms land use, affects environmental resources, and creates new planning challenges. This project investigates where urban expansion occurred between 2020 and 2025 and examines the spatial factors associated with expansion across Bangladesh's city corporations.

## Study Area

The study covers 12 city corporations:

- Barishal
- Chattogram
- Cumilla
- Dhaka North
- Dhaka South
- Gazipur
- Khulna
- Mymensingh
- Narayanganj
- Rajshahi
- Rangpur
- Sylhet

## Research Objectives

1. Map land-use/land-cover patterns for 2020 and 2025.
2. Identify locations where non-built-up land transitioned to built-up land.
3. Examine the associations between urban expansion and selected demographic, accessibility, and topographic factors.
4. Compare model results across the 12 city corporations.

## Methodology

### 1. Land-Use/Land-Cover Analysis
LULC data for 2020 and 2025 are used to identify land-cover transitions.

### 2. Urban Expansion Mapping
Urban expansion is represented as a binary outcome: non-built-up pixels in 2020 that became built-up in 2025 are coded as 1; all other pixels are coded as 0.

### 3. Spatial Predictors
The analysis considers seven predictors:

- Population density
- Distance to existing built-up areas
- Distance to roads
- Distance to water
- Distance to the defined urban core
- Elevation
- Slope

The urban core is operationally defined using the centroid of the largest contiguous built-up patch in 2020.

### 4. Statistical and Machine-Learning Analysis
The planned analytical workflow includes exploratory data analysis, logistic regression, Random Forest classification, and SHAP-based interpretation of model predictions.

## Tools

- Python
- Google Earth Engine
- Remote sensing and GIS
- Statistical modelling
- Machine learning and model interpretation

## Repository Structure

- `02_scripts/` — analysis scripts and modelling workflows.
- `01_data/` — planned documentation of datasets and sources.
- `03_results/` — selected maps, figures, and model outputs.
- `04_documentation/` — variable definitions and methodological notes.

Additional folders and files will be added as the project is documented.

## Reproducibility and Limitations

The analysis is being developed as a reproducible geospatial research workflow. Data availability, spatial resolution, predictor construction, class imbalance, spatial dependence, and validation design need to be considered when interpreting model outputs.

Model explanations identify patterns learned by the fitted models; they do not, by themselves, establish causal relationships. Results should be interpreted in light of the modelling assumptions and validation procedures.

## Project Status

**In progress.** Data processing, modelling, validation, and documentation are being developed.

## Research Context

This project connects urban planning, remote sensing, spatial analysis, and quantitative modelling to investigate patterns of urban growth in Bangladesh.

