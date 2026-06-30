# Nigeria CDR Project

## Overview

This repository contains the reproducible Python workflow developed during my Independent Study on spatial data infrastructure for Carbon Dioxide Removal (CDR) logistics.

The current implementation focuses on building a deployment-site database for Nigeria by integrating multiple spatial datasets into a common 5 km grid.

## Current workflow

- ESA WorldCover processing
- 5 km spatial grid generation
- Land-cover fraction calculation
- Copernicus DEM download
- Elevation extraction
- Slope calculation

## Repository contents
```
data/              # Raw and processed input datasets (large files stored externally)
notebooks/         # Step-by-step processing workflow
outputs/           # Sample outputs produced by the workflow
scripts/           # Standalone processing scripts (future)
requirements.txt   # Python package dependencies
README.md          # Project documentation
.gitignore         # Files excluded from version control
```

## Outputs

The `outputs/tables/` folder contains a **sample** of the generated deployment-site database (`deployment_site_database_v2_sample.csv`).

The complete database and processed raster files are not stored in this repository because of their size. They will be maintained externally (e.g., SharePoint/OneDrive) while this repository provides the fully reproducible workflow required to regenerate them.

## Reproducibility

All processing steps are documented in the notebooks. Running the notebooks in sequence reproduces the deployment-site database from the original input datasets.
