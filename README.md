# 🌫️ GeoAI Bio-Aerosol Prediction — NUST H-12 Islamabad

> **Machine Learning applied to real aerobiological fieldwork data**

[![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=flat&logo=python)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat&logo=jupyter)](https://jupyter.org)
[![Data](https://img.shields.io/badge/Data-Real%20Thesis%20Fieldwork-brightgreen?style=flat)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## 📌 Overview

This project applies **GeoAI and machine learning** to real bio-aerosol field data
from my MS thesis at NUST IGIS (2017). Every data point comes from actual
field measurements — 6 sampling sites, 12 days, April 2016.

**Thesis:** Spatial Distribution of Bio-Aerosols and Determinant Factors
in a Built Environment

**Author:** Fatima Filza Hassan | MS Remote Sensing & GIS, NUST (2017)

**Study Area:** H-12 Sector, NUST Campus, Islamabad (3.28 km²)

---

## 📂 Repository Structure
geoai-bioaerosol-prediction/
├── data/
│   ├── pollen_data.csv              # 72 real pollen measurements
│   ├── fungus_data.csv              # 72 real fungus measurements
│   ├── site_metadata.csv            # GPS coords + LULC variables
│   ├── meteorological_correlations.csv
│   └── species_data.csv             # Alternaria & Aspergillus
└── notebooks/
└── 01_EDA_BioAerosol_NUST.ipynb # Full ML analysis

---

## 
---

## 🤖 Analyses Performed

| Analysis | Method | Key Finding |
|----------|--------|-------------|
| Time Series | Visualization | Site 2 peak pollen: 489/m³ on Apr-04 |
| Site Comparison | Bar charts | Site 1 highest fungus: 3234/m³ |
| LULC Prediction | Random Forest | Grass land % drives fungus concentration |
| Meteorological | Pearson Correlation | Wind speed r=0.60 at open site |
| Spatial Distribution | IDW Interpolation | Significant spatial heterogeneity confirmed |
| Species Analysis | Comparative | Aspergillus + Alternaria = ~70% of fungus |

---

## 🚀 Run in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Filza-coder/geoai-bioaerosol-prediction/blob/main/notebooks/01_EDA_BioAerosol_NUST.ipynb)

---

## 🔬 Real Data Summary

- **6 sampling sites** across NUST H-12 campus
- **12 sampling days** (April 4–20, 2016)
- **33 pollen types** identified
- **14 fungus species** identified
- **Low-cost portable sampler** designed and built by author

---

## 👩‍🔬 Author

**Fatima Filza Hassan**
MS Remote Sensing & GIS — NUST IGIS (2017)
Assistant Registrar, University of the Punjab, Lahore
🌐 [Portfolio](https://Filza-coder.github.io)
