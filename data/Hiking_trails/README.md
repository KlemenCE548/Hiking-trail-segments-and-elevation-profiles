# Hiking_trails

## Description

This shapefile contains 25 hiking trail segments used as input data for Script 1 of the analysis workflow presented in the associated PLOS ONE study. The file corresponds to the dataset named "Hiking_trails" referenced throughout the analysis workflow. Each polyline feature corresponds to a single trail segment included in the analysis.

The dataset was prepared to support reproducibility of the published analyses and represents the trail geometry used in the study.

## File

`Hiking_trails.shp`

## Attributes

| Attribute | Description |
|---|---|
| `FID` | Internal feature identifier assigned by the GIS software. |
| `ID_Path` | Unique identifier of the hiking trail segment. |
| `Macroregion` | Slovenian macroregion in which the trail segment is located. |
| `Difficulty` | Hiking difficulty category. |
| `Shape_Length` | Length of the trail segment (m). |

## Geometry
Polyline ZM

## Coordinate Reference System
Slovenia 1996 / Slovene National Grid (D96/TM)

**Authority:** EPSG:3794

**Linear unit:** Meter

## Software:
ArcGIS Pro 3.6

## Authors:
Klemen Prah, Simona Šinko, and Ashton M. Shortridge

## Date:
November 2026

## Related files:
- `StackProfileResults.csv`
- `S2 File` – Processed data underlying the analyses of the 25 trail segments (XLSX)

## Notes:
The trail segments served as the input dataset for extracting elevation profiles from the 1 m Digital Terrain Model (DTM) used in the associated PLOS ONE study. The elevation profiles derived from these trail segments are provided in `StackProfileResults.csv`.

The published shapefile represents the trail geometry used in the analysis workflow and should not be considered a collection of original field-recorded GPS tracks.
