# Spatial Hotspot Analysis

A small geospatial data analysis demo for detecting spatial and temporal hotspots in timestamped observational data.

The project uses safe synthetic data and demonstrates a compact workflow for:

- loading timestamped latitude/longitude observations
- creating simple spatial grid cells
- aggregating observations over space and time
- visualizing cumulative spatial activity
- estimating spatial density with KDE
- detecting daily hotspot cells with z-score normalization
- tracking persistent buildup with a CUSUM-style score

This repository is intended as a clean, non-proprietary public demo of applied data analysis, uncertainty-aware monitoring, and geospatial reasoning.

## Project structure

```text
spatial-hotspot-analysis/
  data/
    sample_observations.csv
  spatial_hotspot_analysis.ipynb
  README.md
  requirements.txt
```

## Data

The included dataset is synthetic and created only for demonstration. It does not contain private, operational, client, or company-specific information.

## Tools

Python, pandas, NumPy, scikit-learn, matplotlib.

## How to run

Install the dependencies:

```bash
pip install -r requirements.txt
```

Open the notebook:

```bash
jupyter notebook spatial_hotspot_analysis.ipynb
```
