# 🌱 NEE-DATA-KIT

This repository provides tools to download and explore environmental datasets commonly used as predictors in Net Ecosystem Exchange (NEE) modeling over the Amazon region. It includes workflows for accessing remote sensing and reanalysis data (MODIS, ERA5, FluxCom), as well as initial visualization of the downloaded files.

---


## 📘 Notebooks

### `download_gee_era5_modis_fluxcom.ipynb`
This notebook includes scripts to download raw data from:
- Google Earth Engine (e.g., MODIS vegetation indices, LAI)
- ERA5 reanalysis (temperature, radiation, precipitation)
- NASA CERES radiation products
- INPE MERGE rainfall data
- FluxCom (NEE estimates from machine learning models)

> ⚠️ This notebook **only performs data download**. No preprocessing is included.

---

### `opening_fluxnet_lba_fluxcom_predictors_data.ipynb`
This notebook loads previously downloaded data and performs:
- Opening and inspecting NetCDF or CSV files
- Exploring variable dimensions and units
- Visualizing time series or maps (optional)
- Checking data completeness and formats

It includes examples using:
- Flux tower data (LBA/FLUXNET)
- ERA5, MODIS, and FluxCom predictors

---

## 🔧 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
