[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nishani53/Khanal_MSc_Thesis_MSU/blob/main/Khanal_MSU_project_Hotspot_area_1980s-2020s/Khanal_MSU_project_hotspot_area_1980s_2020s.ipynb)

# 🌲 Forest Product Market Coverage & Competition Intensity Analysis (Michigan, 1980s–2020s)

This project analyzes the **spatial extent of forest market coverage** and **competition intensity** across four major forest product types in Michigan:  
- 🌳 **Hardwood Sawlogs**  
- 🌲 **Softwood Sawlogs**  
- 🧻 **Pulpwood & Chips**  
- 🔥 **Wood Biomass**  

The analysis spans multiple decades (1980s–2020s) and quantifies how much **forested area** falls within procurement zones of varying **market competition levels** — from **highest (Level 5)** to **lowest (Level 1)**.

---

## 📌 Objective

To estimate, for each forest product and each decade:
- The **extent of forestland (in acres)** covered by procurement zones.
- The **distribution of forest types** within these zones.
- How market **competition intensity** affects geographic reach and forest access.

---

## 🗂️ Data Sources

### 1. 📐 Market Coverage Shapefiles
- Separate shapefiles for each:
  - Forest product (Hardwood, Softwood, Biomass, Pulpwood)
  - Decade (1980s, 1990s, 2000s, 2010s, 2020s)
  - Competition level (1 to 5; 5 = highest competition)
- Represent estimated procurement zones around active mills.

### 2. 🗺️ Forest Cover Rasters
- Forest type classification raster for each decade.
- Pixel values represent forest type codes (e.g., Aspen/Birch, Maple/Beech/Birch).
- Resolution: 30m per pixel (or similar).

---

## ⚙️ Method Overview

1. **Reproject** all shapefiles to match the raster CRS.
2. For each shapefile (product × decade × competition level):
   - **Clip** the forest raster using the polygon.
   - **Mask** non-forested or irrelevant classes.
   - **Count** pixels by forest type.
   - **Convert** pixel counts to area in acres.
3. **Aggregate results** across levels, decades, and products for comparison.

---

## 📦 Tools & Libraries

This analysis was implemented using Python and the following libraries:

- `rasterio` – Raster I/O, masking
- `fiona` – Shapefile access
- `shapely` – Geometry operations
- `pyproj` – CRS projection
- `geopandas` – Spatial dataframes
- `numpy` – Array math and pixel counting
- `pandas` – Tabular summaries

---

## 📊 Output

For each **decade × product × competition level**, the output includes:
- Total forest area (acres) within market zones
- Area breakdown by forest type (e.g., conifer vs. deciduous)
- Summary tables (CSV) and optional visualizations

---

## 📁 Folder Structure

