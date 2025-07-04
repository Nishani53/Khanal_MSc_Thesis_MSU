[![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nishani53/Khanal_MSc_Thesis_MSU/blob/main/Khanal_MSU_project_market_change_1980s-2020s/Khanal_MSU_project_market_coverage_change_1980s-2020s.ipynb)

# 🧭 Forest Market Footprint Change in Michigan (1980s–2020s)

This analysis evaluates **how the spatial extent of forest product markets has changed across Michigan** from the **1980s through 2023**. By combining mill procurement zones for all major forest products into **decade-wide market coverage maps**, and comparing those across time, this project identifies where markets were **retained**, **lost**, or **gained**.

---

## 📌 Objective

To understand long-term market trends by analyzing the **presence and shifts in overall procurement coverage**, rather than competition intensity.

---

## 🪵 Forest Products Included

- 🌳 Hardwood Sawlogs  
- 🌲 Softwood Sawlogs  
- 🧻 Pulpwood  
- 🔥 Wood Biomass  

Each product’s procurement zone (based on haul distance/time) was merged to form **comprehensive market coverage** per decade.

---

## 🔍 Key Spatial Categories

By comparing the combined market zones from earlier decades to 2023, we identify:

| Category | Description |
|----------|-------------|
| 🟩 **Market Retained** | Areas that were within market zones in previous decades and remained so in 2023. |
| 🟥 **Market Loss**     | Areas that were within historical market zones but are no longer served in 2023. |
| 🟦 **Market Gained**   | New areas included in the 2023 market zone that were not previously served. |

These categories help evaluate the **geographic stability, contraction, or expansion** of the industry over time.

---

## 🛠️ Methodology Summary

1. **Dissolve** all forest product zones per decade into a single market footprint.
2. **Overlay** historical and 2023 market polygons using spatial operations.
3. Classify areas into retained, lost, or gained categories.
4. Output maps for visualization and spatial analysis.

### Tools Used

- **Python**
- **GeoPandas**
- **Shapely**
- **Fiona**
- **Matplotlib**

---

## 🗂️ Time Periods Compared

Market changes were analyzed across the following decades:

- 📼 **1980s**
- 📀 **1990s**
- 💾 **2000s**
- 💻 **2010s**
- 📱 **2023 (Current)**

---

## 📈 Use Cases

- Identifying areas of long-term market resilience or decline  
- Planning outreach or investment in newly gained or underserved regions  
- Supporting infrastructure, forest access, and policy decisions  
- Understanding long-term forest industry dynamics in Michigan

---

## 📧 Contact

For access to maps, spatial datasets, or further collaboration:

**Naresh Khanal**  
✉️ [khanalna@msu.edu](mailto:khanalna@msu.edu)  
📍 Michigan State University

---

## 📎 License

This analysis is intended for **academic and research use only**.  
Please contact the author before redistribution or reuse.
