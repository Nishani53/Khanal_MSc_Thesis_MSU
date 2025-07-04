[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nishani53/Khanal_MSc_Thesis_MSU/blob/main/Khanal_MSU_project_forest_cover_area_1980s-2020s/Khanal_MSU_project_forest_cover_area_1980s-2020s.ipynb)

# 🌲 Forest Market Coverage & Forest Area Overlay Analysis

This notebook quantifies the actual **forest area** within the **procurement zones** of different forest product markets in **Michigan**, across multiple timeframes. It also identifies how much forest land was **retained**, **lost**, or **newly added** to market coverage between decades, broken down by **forest type**.

---

## 📌 Objective

To accurately assess the forestland included within market coverage zones for:

- 🌳 **Hardwood Sawlogs**
- 🌲 **Softwood Sawlogs**
- 🧻 **Pulpwood**
- 🔥 **Biomass**

This is done by spatially overlaying **vector shapefiles** (market zones) with a **classified forest type raster**, and calculating area (in acres) by forest group.

---

## 🗺️ Data Sources

### 1. **Forest Market Coverage Shapefiles**
- Represent procurement zones around mills during different decades.
- Include classifications for:
  - Retained market areas
  - Lost market areas
  - Newly added areas

### 2. **Forest Type Raster**
- A thematic raster where each pixel is labeled with a forest type group (e.g., Aspen/Birch, Oak/Hickory).
- ~30m spatial resolution.
- Pixel values are numeric codes, mapped to forest group names.

---

## 🧠 Method Overview

1. 📐 Reproject shapefiles to match raster CRS.
2. ✂️ Clip the raster with each polygon using spatial masking.
3. 🔍 Identify valid forest pixels within each zone.
4. 📊 Count pixels by forest type and convert to **acres**.
5. 🧾 Print forest area results per polygon and total them for analysis.

---

## 🛠️ Python Libraries Used

- [`rasterio`](https://rasterio.readthedocs.io/) – raster access and masking
- [`fiona`](https://fiona.readthedocs.io/) – shapefile I/O
- [`shapely`](https://shapely.readthedocs.io/) – geometry manipulation
- [`pyproj`](https://pyproj4.github.io/pyproj/stable/) – coordinate transformations
- [`numpy`](https://numpy.org/) – efficient array and count operations

---

## 📈 Output Example

For each zone (e.g., "Biomass Market Lost 1985–2023"):

- 🔢 **Forest area by type**, in acres
- 📏 **Total forest area** per zone
- 📊 Aggregated statistics across all zones

---

## 📂 Project Structure

