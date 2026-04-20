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
>
> <section>
    <h2 id="methodology">🛠️ Section 2: Methodology</h2>
    <p>
        The research methodology is centered on the <b>post-classification change detection</b> approach[cite: 225]. Using the <b>ArcGIS Pro</b> platform, multispectral satellite data was processed to monitor environmental shifts[cite: 220, 226].
    </p>
    <ul>
        <li><b>Classification Scheme:</b> The region was classified into seven primary categories: <i>Crops, Water, Built Area, Rangeland, Trees, Flooded Vegetation,</i> and <i>Bare Ground</i>[cite: 226, 227].</li>
        <li><b>Spatial Reference:</b> The <b>WGS 84 / UTM zone 42N</b> coordinate system was utilized to maintain geometric accuracy and minimize distortion during area calculations[cite: 227].</li>
        <li><b>Data Integration:</b> The study combined <b>Sentinel-2</b> (10m resolution) imagery with <b>Esri LULC</b> datasets for high-precision mapping[cite: 181, 184].</li>
    </ul>
</section>

<hr>

<section>
    <h2 id="results">📊 Section 3: Results and Discussion</h2>
    <p>
        Statistical analysis highlights a significant transformation in the Syrdarya region's land fund between 2017 and 2024[cite: 253].
    </p>

    <div align="center">
        <img src="images/Trend Analysis Map (2017-2024).jpg" alt="LULC Dynamics" width="100%">
        <p><i>Figure 2. Land Use and Land Cover (LULC) dynamics maps of the Syrdarya region[cite: 250].</i></p>
    </div>

    <h3>Urbanization Trends:</h3>
    <p>
        The most pronounced growth was observed in the <b>Built Area</b> category, which expanded from <b>41,841.5 hectares</b> in 2017 to <b>49,212.9 hectares</b> in 2024[cite: 254]. This represents a sharp <b>17.6% increase</b> in urban footprint[cite: 307].
    </p>

    <h3>Agricultural Shifts:</h3>
    <p>
        While <b>Crops</b> remain the dominant category, their total area exhibited a declining trend, decreasing from <b>385,527.9 hectares</b> to <b>365,581.6 hectares</b>[cite: 253, 257, 258].
    </p>
</section>

<hr>

<section>
    <h2 id="transition">🔄 Section 4: Inter-Class Transition Analysis</h2>
    <p>
        Analysis via the <b>Sankey diagram</b> illustrates the specific trajectories of land transformation[cite: 272, 275].
    </p>

    <div align="center">
        <img src="images/Sankey_Diagram.png" alt="Sankey Diagram" width="85%">
        <p><i>Figure 3. LULC classification trajectory and transition flows in hectares.</i></p>
    </div>

    <p>
        A substantial portion of cropland was transformed into <b>rangeland</b> and <b>urban development</b> zones, driven by both socioeconomic pressure and hydrological shifts[cite: 275, 308].
    </p>
</section>

<hr>

<section>
    <h2 id="conclusion">🎓 Section 5: Conclusion</h2>
    <ul>
        <li><b>Rapid Urbanization:</b> The 17.6% expansion of built-up areas necessitates the immediate updating of digital cadastre maps[cite: 307].</li>
        <li><b>Methodological Efficiency:</b> Integrating <b>Sentinel-2</b> with <b>ArcGIS Pro</b> is approximately <b>80% faster</b> and more precise than traditional terrestrial geodetic methods[cite: 309].</li>
        <li><b>Practical Application:</b> These findings serve as a strategic resource for the <b>National Cadastre Agency</b> to optimize land resource allocation[cite: 310].</li>
    </ul>
</section>
