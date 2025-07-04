[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nishani53/Khanal_MSc_Thesis_MSU/blob/main/Khanal_MSU_project_Competition_hotspot_example/Khanal_MSU_project_competition_hotspot_example_2023.ipynb)

# 🔥 Forest Product Competition Hotspots in Michigan – 2023 Example

This Python script demonstrates how **competition hotspots** were calculated for **forest product markets in Michigan (2023)** using spatial analysis and mill proximity modeling.

It provides a **template for competition mapping**, including haul distance estimation, competition scoring, and hotspot classification — applied individually to each major forest product type.

---

## 🌲 Forest Product Categories Analyzed (2023)

- 🌳 **Hardwood Sawlogs**
- 🌲 **Softwood Sawlogs**
- 🧻 **Pulpwood**
- 🔥 **Wood Biomass**

Each product was analyzed **separately**, with competition zones mapped based on mill access and haul-time thresholds.

---

## 🏁 Competition Level Classification

| Level | Description |
|-------|-------------|
| 🟦 **Level 1** | Very Low Competition – minimal mill access |
| 🟩 **Level 2** | Low Competition – few overlapping haul zones |
| 🟨 **Level 3** | Moderate Competition – multiple mill options nearby |
| 🟧 **Level 4** | High Competition – dense overlap of mill haul zones |
| 🟥 **Level 5** | Very High Competition (Hotspot) – intense market activity |

These zones represent the **merchantability and market accessibility** of feedstock in various forested areas.

---

## 🛠️ Workflow Summary

For each product:

1. 📍 Load mill locations and road networks  
2. 🛣️ Generate haul-distance buffers (cost proxies)  
3. 🧮 Rasterize or grid the area into zones of mill overlap  
4. 🎯 Classify into 5 competition levels based on overlap counts  
5. 🗺️ Visualize and export hotspot maps  

---

## 📦 Tools & Libraries

- **Python 3**
- `geopandas`
- `shapely`
- `rasterio`
- `matplotlib`
- `networkx` (for road-based distance modeling)
- `osmnx` (optional, for custom road networks)

---

## 📂 Output

Each forest product produces a:
- **Shapefile** of competition zones  
- **Map** showing color-coded competition levels  
- **CSV summary** (optional)

These results can be used in standalone form or compared against historical decades for market change analysis.

---

## 📧 Contact

For support or questions:

**Naresh Khanal**  
✉️ [khanalna@msu.edu](mailto:khanalna@msu.edu)

---

## 📎 License

This script is for research and demonstration purposes.  
Contact the author before reuse or redistribution.
