# 🛰️ Spatio-Temporal Analysis of LULC: Syrdarya Region (2017–2024)

## 📍 Section 1: Study Area and Geographic Setting

The success of any geospatial analysis depends on a clearly defined study area. For this research, the **Syrdarya Region** of Uzbekistan was selected due to its unique transition from a traditional agricultural hub to a rapidly urbanizing industrial zone.

---

### 🗺️ Study Area Visualization
<p align="center">
<img src="images/Study%20Area.jpg" width="600" alt="Syrdarya Study Area Map">
  <br>
  <b>Figure 1. Administrative boundary of Syrdarya region and detailed urban layout of Gulistan city.</b>
</p>

---

### 🌍 Geographic Overview
Syrdarya region is situated in the central part of Uzbekistan, on the left bank of the **Syr Darya River**. It serves as a vital corridor connecting the Fergana Valley with the rest of the country.

* **📏 Total Area:** Approximately **4,280 km²**.
* **🏛️ Administrative Structure:** The region consists of **11 administrative districts** (Akaltyn, Bayaut, Gulistan, Mirzaabad, Sayhunabad, Sardoba, Syrdarya, Khavast, Boyovut, and others) and the regional center—**Gulistan city**.
* **📈 Significance:** While the economy is historically based on agriculture (cotton, grain, and melons), the period between **2017 and 2024** has shown a significant shift toward rapid industrialization.

### 🛠️ GIS Methodology for Site Characterization
The map above was developed using **ArcGIS Pro** to establish the spatial baseline for the LULC (Land Use and Land Cover) analysis:

1.  **Vector Data Integration:** Administrative boundaries were sourced from the **National Cadastre Agency** database to ensure legal and spatial accuracy.
2.  **Coordinate System:** To maintain geometric integrity and minimize distortion during area calculations, the **WGS 1984 UTM Zone 42N** projection was applied.
3.  **Visualization:** The central inset map focuses on **Gulistan city**, providing a high-resolution view of the urban fabric. This serves as the *"Ground Truth"* reference for identifying the **"Built Area"** class during satellite imagery classification.
4.  **Cartographic Design:** Professional symbology distinguishes between administrative borders, transportation networks, and residential clusters for clear infrastructure interpretation.

### 🔬 Why Syrdarya? (Research Motivation)
According to the research, the Syrdarya region represents a critical **"socio-ecological laboratory."** * **Hydrology:** The presence of the Syr Darya river provides complex hydrological dynamics.
* **Socioeconomics:** Proximity to **Tashkent (the capital)** drives intense socioeconomic pressure on land resources. 

> This map establishes the spatial **"Stage"** where we analyze how every hectare of land has transformed over the last 8 years.

## 🛰️ Section 2: Spatio-Temporal LULC Dynamics (2017–2024)

This section presents the core findings of the land-use classification. By leveraging multi-temporal **Sentinel-2** satellite imagery and **Esri LULC** datasets, we mapped the evolution of the Syrdarya region over an eight-year period.

---

### 🗺️ Multi-Year Land Cover Comparison
<p align="center">
  <img src="images/SYRDARYA1.jpg" width="600" alt="LULC Dynamics 2017-2024">
  <br>
  <b>Figure 2. Spatio-temporal distribution of LULC classes in Syrdarya Region (2017, 2020, 2022, and 2024).</b>
</p>

---

### 🔍 Classification Methodology
To ensure high thematic accuracy, the following workflow was implemented in **ArcGIS Pro**:

1.  **Data Source:** High-resolution (10m) **Sentinel-2** imagery was utilized for its superior spectral bands, essential for distinguishing between subtle land cover types.
2.  **Classification Schema:** We identified 7 primary classes:
    * 🔴 **Built Area:** Residential, industrial, and infrastructure zones.
    * 🌾 **Crops:** Active agricultural lands and irrigated fields.
    * 🌿 **Rangeland:** Natural grasslands and shrubs.
    * 🌳 **Trees:** Orchards and forested areas.
    * 💧 **Water:** Rivers (Syr Darya), canals, and reservoirs.
    * 🌱 **Flooded Vegetation:** Wetlands and seasonal floodplains.
    * 🏜️ **Bare Ground:** Exposed soil and non-vegetated areas.
3.  **Accuracy Assessment:** Post-classification cleaning was performed to remove "salt-and-pepper" noise, ensuring the maps reflect real-world geographical patterns.

### 📈 Key Visual Observations
* **Urban Sprawl (Built Area):** A clear intensification of red pixels is visible around the central and southern districts. This confirms the **17.6% growth** in urban footprint mentioned in our statistical analysis.
* **Agricultural Shift:** While **Crops** remain the dominant class (occupying the majority of the map), the spatial distribution shows fragmentation, especially in areas transitioning into built environments or rangelands.
* **Hydrological Fluctuations:** The **Water** and **Flooded Vegetation** classes show dynamic shifts along the Syr Darya riverbanks, reflecting seasonal variations and regional water management policies during the study period.

> **Scientific Insight:** The use of the **Post-Classification Change Detection** method allows us to not only see *that* change happened but specifically *where* and *to what extent* the land was transformed.


## 📊 Section 3: Quantitative Statistical Analysis

While visual maps provide a spatial overview, quantitative data is essential for understanding the precise magnitude of land cover transformations. This section breaks down the numerical shifts across all 7 LULC classes between **2017 and 2024**.

---

### 📉 LULC Class Distribution and Trends
<p align="center">
  <img src="images/LULC%20Statistical%20Analysis%20Chart.jpg" width="600" alt="Statistical Chart 2017-2024">
  <br>
  <b>Figure 3. Comparative statistical distribution of land cover areas (in hectares) for 2017 and 2024.</b>
</p>

---

### 📋 Detailed Area Statistics
Based on the geoprocessing results from **ArcGIS Pro**, the following table summarizes the changes in the Syrdarya Region:

| LULC Class | 2017 Area (Ha) | 2024 Area (Ha) | Change (%) | Trend |
| :--- | :---: | :---: | :---: | :---: |
| 🔴 **Built Area** | 41,841.5 | 49,212.9 | **+17.6%** | 📈 Increase |
| 🌾 **Crops** | 385,504.6 | 365,567.1 | -5.2% | 📉 Decrease |
| 🌿 **Rangeland** | 20,404.1 | 30,195.9 | +48.0% | 📈 Increase |
| 💧 **Water** | 10,753.8 | 12,058.4 | +12.1% | 📈 Increase |
| 🌱 **Flooded Veg** | 1,849.2 | 1,731.8 | -6.3% | 📉 Decrease |
| 🌳 **Trees** | 1,327.3 | 1,029.3 | -22.4% | 📉 Decrease |
| 🏜️ **Bare Ground** | 1,444.6 | 3,329.7 | +130.5% | 📈 Increase |

### 🔍 Scientific Interpretation of Findings

1.  **Urbanization Dynamics (Built Area):** The most critical finding is the **7,371-hectare expansion** of Built Areas. This 17.6% growth is primarily driven by national housing programs and industrial zone developments (e.g., in Gulistan and Yangiyer). For the **National Cadastre Agency**, this necessitates rapid digital map updates to ensure accurate land taxation and infrastructure planning.

2.  **Agricultural Pressure (Crops):** The decrease in nearly **20,000 hectares** of cropland is a significant indicator of urban sprawl consuming fertile soils. As land is converted from "Crop" to "Built Area," the region faces a long-term challenge in maintaining agricultural productivity.

3.  **Land Degradation and Rangeland Growth:** The sharp increase in **Rangeland** and **Bare Ground** suggests that some previously cultivated or vegetated areas are undergoing aridification or seasonal abandonment. This highlights the need for sustainable land management in the Aral Sea Basin's ecological context.

4.  **Hydrological Stability:** The slight increase in **Water** area (12.1%) is likely linked to improvements in irrigation reservoir management or seasonal overflow from the Syr Darya river during the 2024 observation window.

> **Conclusion:** The quantitative data confirms that the Syrdarya region is transitioning from a purely agrarian landscape to a mixed urban-industrial region. This shift requires 80% faster monitoring cycles, which is now possible thanks to the **Sentinel-2 pipeline** established in this research.
