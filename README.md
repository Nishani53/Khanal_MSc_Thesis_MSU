# 🌲 Forest Product Market Competition & Coverage in Michigan (1980s–2020s)

### 📧 Contact
**Naresh Khanal**  
✉️ *khanalna@msu.edu*  
📍 *Michigan State University*

**Major Supervisor**  
**Dr. Raju Pokharel**  
✉️ *raju2020@msu.edu*  
🌐 *Michigan State University*

---

This repository provides a comprehensive spatial analysis of **forest product market competition and coverage trends across Michigan** from the 1980s through the 2020s. Using road networks, haul-time modeling, and mill datasets, the project maps how mill proximity and market access have shifted over time — with a focused, high-resolution case study for **2023**.

---

## 📁 Project Structure

### 1. **Competition Hotspot Mapping (1980s–2020s)**
Analyzes competition intensity for four key forest product categories by decade:
- 🌳 Hardwood Sawlogs
- 🌲 Softwood Sawlogs
- 🧻 Pulpwood
- 🔥 Wood Biomass

Competition levels (1–5) are assigned based on overlapping mill procurement zones, with **Level 5 indicating high market pressure or hotspots**.

### 2. **2023 Competition Hotspot Example**
Demonstrates the **full competition scoring and mapping process** using only 2023 data. This serves as a reusable template for other years/products.

Steps include:
- Haul buffer generation using road networks
- Mill overlap scoring
- Zone classification (Levels 1–5)
- Export of shapefiles, maps, and summary statistics

### 3. **Mill Facility Mapping (1980s–2020s)**
Visualizes spatial distribution, types, and capacities of wood-processing mills across Michigan for each decade:
- Sawmills
- Pulp mills
- Biomass plants
- Veneer/plywood mills

Supports spatial context for competition and coverage analysis.

### 4. **Forest Market Coverage & Forest Area Overlay**
Quantifies forestland included within mill procurement zones across decades by overlaying vector zones on a **classified forest-type raster**. Outputs include:
- Forest area (acres) by type
- Retained, lost, or newly added zones
- Forest access by product type

### 5. **Forest Market Footprint Change Analysis**
Assesses **how total market coverage has changed** across decades by comparing merged product procurement zones:
- 🟩 Retained Market Areas
- 🟥 Lost Market Areas
- 🟦 Gained Market Areas

Outputs include side-by-side maps and summary statistics by time period.

---

## 🛠️ Tools & Libraries Used

- Python 3
- GeoPandas
- Shapely
- Fiona
- Rasterio
- NetworkX
- OSMnx (optional)
- Matplotlib
- NumPy

---

## 🗺️ Time Periods Analyzed

- 📼 1980s  
- 📀 1990s  
- 💾 2000s  
- 💻 2010s  
- 📱 2023  

---

## 📊 Use Cases

- Strategic siting of forest product mills  
- Market pressure & sustainability analysis  
- Resource planning for policy or industry  
- Benchmarking long-term market evolution  

---

## 🚀 Getting Started

1. **Clone this repository**
2. **Install dependencies**  
   ```bash
   pip install -r requirements.txt

