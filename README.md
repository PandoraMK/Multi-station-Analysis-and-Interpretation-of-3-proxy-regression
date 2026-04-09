# Multi-Proxy Ionospheric TEC Trend Analysis

This project performs multi-proxy regression analysis on ionospheric Total Electron Content (TEC) data using solar activity proxies (F10.7, MgII, and Sunspot Number) to estimate long-term TEC trends.

The script processes GNSS-derived TEC data, removes seasonal components, applies regression modelling, and evaluates solar proxy contributions to ionospheric variability.

---

## Project Overview

The model estimates TEC using a multi-proxy regression approach:

TEC = const + β₁·t + β₂·F10.7 + β₃·MgII + β₄·SNN + ε

Where:

- TEC = Total Electron Content (TECU)
- t = time (years)
- F10.7 = Solar radio flux
- MgII = Magnesium II index
- SNN = Sunspot number
- ε = residual error

The goal is to:

- remove seasonal effects from TEC
- quantify solar proxy influence
- estimate long-term TEC trends
- evaluate model performance
- compute proxy contributions using partial R²
- generate publication-ready plots

---

## Key Features

- Multi-station TEC analysis
- Seasonal decomposition
- Solar proxy regression
- Partial R² analysis
- Solar-corrected TEC trends
- Residual diagnostics
- Monthly and yearly analysis
- Automatic plot generation
- Export of results and figures

---

## 📁 Project Structure
