# QGIS Project

This directory documents the QGIS workflow used for the Kano groundwater stress analysis.

## Software

- QGIS 3.44.13-Solothurn
- GDAL 3.13.2
- GEOS 3.14.1
- PROJ 9.8.1
- Python 3.12.13

## Main QGIS layers

- Kano State boundary
- Kano LGA administrative boundaries
- 2024 vegetation stress
- 2025 vegetation stress
- 2024 rainfall stress
- 2025 rainfall stress
- Combined groundwater stress for 2024
- Combined groundwater stress for 2025
- LGA-level groundwater stress results
- 2025 minus 2024 stress change

## LGA-level analysis

Mean groundwater stress was calculated for each of the 44 Local Government Areas (LGAs) in Kano State for 2024 and 2025.

Stress change was calculated as:

2025 stress − 2024 stress

Positive values represent an increase in stress, while negative values represent a decrease.

## Final map

The final cartographic product is:

`Kano_Groundwater_Stress_Change_2024_2025.pdf`

The map uses a blue–white–red diverging colour scheme:

- Blue — decrease in stress
- White — little/no change
- Red — increase in stress

The final map also includes LGA boundaries, Kano State boundary, legend, north arrow, scale bar, and data source information.
