[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/your-username/your-repo-name/blob/main/your-notebook-name.ipynb)

# 🏭 Mill Facility Mapping in Michigan (1980s–2020s)

This project visualizes the **spatial distribution and operational capacity** of forest product milling facilities across **Michigan**, from the **1980s through the 2020s**. The interactive or static maps show different facility types and size categories over time, helping users understand the evolution of industrial wood processing infrastructure.

---

## 📌 Overview

The script processes and maps the following:

- 📍 **Facility Locations** by decade (1980s, 1990s, 2000s, 2010s, 2020s)
- 🪓 **Facility Types** such as:
  - Sawmills
  - Pulp mills
  - Biomass/energy facilities
  - Veneer/plywood plants
- 🧱 **Capacity Categories** (e.g., small, medium, large), based on throughput or size
- 🗺️ **Michigan State Boundary** for reference

---

## 🧠 Purpose

This analysis supports:

- Visualizing **historical shifts** in mill infrastructure
- Understanding spatial **market presence and industrial capacity**
- Linking mill data with **harvest competition zones**
- Informing forest policy, resource planning, or market investment

---

## 📁 Contents

- `*.ipynb`: Python notebook for processing, styling, and displaying mill data
- Shapefiles or GeoPackages of facilities by decade (assumed as inputs)
- Optional: CSVs with mill attributes, such as capacity and type

---

## 🚀 How to Use

1. Clone the repository or download the notebook.
2. Install required libraries (see below).
3. Place all input shapefiles (by decade) in the correct file paths.
4. Run the notebook to generate maps for each time period.

### 🛠️ Required Libraries

```bash
pip install geopandas matplotlib shapely
