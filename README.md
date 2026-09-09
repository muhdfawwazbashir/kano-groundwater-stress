# Kano Groundwater Stress Change Analysis, 2024–2025

## Overview

This repository documents an open-source geospatial analysis of groundwater-related environmental stress across Kano State, Nigeria, between 2024 and 2025.

The analysis integrates vegetation condition derived from Sentinel-2 Normalized Difference Vegetation Index (NDVI) data with rainfall information from the Climate Hazards Group InfraRed Precipitation with Station data (CHIRPS).

The resulting stress indicators were combined to produce annual groundwater stress surfaces for 2024 and 2025. The change between the two years was subsequently evaluated at the Local Government Area (LGA) level for all 44 LGAs in Kano State.

The project was developed using QGIS and Python-based geospatial processing.

---

## Study Area

The study covers **Kano State, Nigeria**, and its **44 Local Government Areas (LGAs)**.

The LGA-level analysis provides a spatially detailed assessment of how the combined stress indicator changed between 2024 and 2025.

---

## Research Aim

The aim of this project is to assess the spatial and temporal change in groundwater-related environmental stress across Kano State between 2024 and 2025 using remotely sensed vegetation conditions and rainfall information.

---

## Objectives

The analysis was designed to:

1. Derive vegetation condition information from Sentinel-2 NDVI observations.
2. Characterize annual rainfall conditions using CHIRPS precipitation data.
3. Develop vegetation-stress and rainfall-stress indicators.
4. Combine the stress indicators to produce annual groundwater-stress surfaces.
5. Compare groundwater stress between 2024 and 2025.
6. Calculate mean stress values for each of Kano State's 44 LGAs.
7. Classify the magnitude and direction of stress change.
8. Produce a final cartographic representation of groundwater stress change.

---

## Data Sources

### Sentinel-2 NDVI

Sentinel-2 satellite imagery was used to derive NDVI observations representing vegetation condition.

The project includes annual NDVI products for:

- 2024
- 2025

NDVI was used as an indicator of vegetation response to environmental conditions.

### CHIRPS Rainfall

CHIRPS precipitation data were used to characterize rainfall conditions for:

- 2024
- 2025

Rainfall information was processed to develop annual rainfall-stress indicators.

### Administrative Boundaries

Kano State and Local Government Area boundaries were used for spatial analysis and cartographic presentation.

---

## Analytical Workflow

The overall workflow consisted of the following stages:

```text
Sentinel-2 imagery
        │
        ▼
     NDVI data
        │
        ▼
Vegetation stress
        │
        ├──────────────┐
        │                │
        ▼               ▼
CHIRPS rainfall   Rainfall stress
        │                │
        └───────┬──────┘
                ▼
       Combined stress
                │
        ┌───────┴───────┐
        ▼                ▼
  2024 stress       2025 stress
        │                 │
        └───────┬───────┘
                ▼
      2025 − 2024 change
                │
                ▼
       LGA-level analysis
                │
                ▼
      Final change map
