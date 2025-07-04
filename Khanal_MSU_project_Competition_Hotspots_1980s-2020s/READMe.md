# 🌲 Competition Hotspot for Forest Products in Michigan (1980s–2020s)

This Python-based spatial analysis identifies **market competition hotspots** for forest products across **Michigan** from the **1980s through the 2020s**. Using **existing road networks** and **haul time as a proxy for cost**, the model visualizes competitive intensity among mills for various forest products across five decades.

---

## 📌 Overview

The analysis covers the following **forest product categories**:

- 🌳 **Hardwood Sawlogs**
- 🌲 **Softwood Sawlogs**
- 🧻 **Pulpwood**
- 🔥 **Wood Biomass**

Each product's competition is mapped using haul-distance thresholds, helping reveal areas where feedstock from forests faces varying levels of market access and pressure over time.

---

## 🏁 Competition Levels Explained

The model assigns a **competition level (1 to 5)** based on overlapping mill haul zones and market density:

| Level | Description |
|-------|-------------|
| 🟦 **Level 1** | **Very Low Competition** – Few or no nearby mills; limited market options (low merchantability). |
| 🟩 **Level 2** | **Low Competition** – Minimal overlap in haul zones; limited competition for feedstock. |
| 🟨 **Level 3** | **Moderate Competition** – Some competition; feedstock has a few potential buyers. |
| 🟧 **Level 4** | **High Competition** – Multiple mills overlap; significant buyer presence. |
| 🟥 **Level 5** | **Very High Competition (Hotspot)** – Strong market competition; high merchantability and pressure on local resources. |

> 🎯 **Hotspot zones** (Level 5) indicate the most economically valuable — and most contested — areas for sourcing forest products.

---

## 🗓️ Time Series Coverage

This project visualizes **decadal competition maps** for Michigan’s forest products, covering:

- 📼 **1980s**
- 📀 **1990s**
- 💾 **2000s**
- 💻 **2010s**
- 📱 **2020s**

Each map highlights spatial shifts in market accessibility and competition pressure.

---

## 🛣️ Methodology

- GIS shapefiles represent mill market zones for each decade.
- Haul time is calculated from road networks as a cost proxy.
- Zones are ranked and classified into competition levels.
- Tools used include: **Python**, **GeoPandas**, **NetworkX**, **OSMnx**, and **rasterio**.

---

## 📊 Use Cases

- Strategic siting of new forest product facilities  
- Identifying underserved or over-saturated markets  
- Forest resource sustainability & long-term planning  
- Competitive benchmarking for policy and industry decisions

---

## 🚀 Getting Started

1. Clone this repository  
2. Install dependencies listed in `requirements.txt`  
3. Update shapefile paths in the script(s)  
4. Run the Python scripts for each forest product and decade  

---

## 📘 Focused Workflow: Competition Hotspots for 2023

Although the full project spans five decades, a **detailed, high-resolution analysis was performed for the year 2023**, including:

- Creating haul-time buffers around mills based on current road networks  
- Mapping individual competition zones by forest product  
- Assigning grid-based competition scores from mill overlap  
- Merging competition zones across products  
- Classifying competition levels (1–5) for final hotspot maps  

This 2023-specific workflow serves as a benchmark for comparison and forms the core reference layer for **market change assessments** across decades.

---

## 📧 Contact

For access to data or high-resolution maps from any decade, please contact:

**Naresh Khanal**  
✉️ [khanalna@msu.edu](mailto:khanalna@msu.edu)

---

## 📎 License

This project is intended for academic and research use only.  
Please reach out for collaboration, permissions, or redistribution.
