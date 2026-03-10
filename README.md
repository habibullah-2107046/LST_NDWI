# Land Surface Temperature (LST) and NDWI Map of Rajshahi Division

![LST and NDWI Map](LST_NDWI.jpg)

## Overview

This repository presents **Land Surface Temperature (LST)** and **Normalized Difference Water Index (NDWI)** maps of **Rajshahi Division, Bangladesh** derived from **Landsat-8 satellite imagery**.

The maps illustrate the spatial distribution of **surface temperature patterns** and **surface water presence** across the region. These indices are widely used in **environmental monitoring, urban climate studies, and water resource analysis**.

The analysis provides insight into the **thermal characteristics of the landscape** and the **distribution of water bodies**, which are important for understanding regional environmental conditions.

---

## Map Components

The figure contains two spatial datasets:

### Land Surface Temperature (LST)

LST represents the **radiative skin temperature of the Earth's surface** and is commonly used to analyze:

- Urban heat island effects
- Surface thermal variation
- Land cover impacts on temperature

Higher values indicate **warmer surface temperatures**, typically associated with **urban areas, bare land, and dry surfaces**.

---

### Normalized Difference Water Index (NDWI)

NDWI is used to detect **surface water bodies and moisture conditions**.

It is calculated using the formula:

```
NDWI = (Green - NIR) / (Green + NIR)
```

Higher NDWI values indicate **water bodies or high moisture content**, while lower values represent **dry land surfaces**.

---

## Data Source

Satellite data used in this analysis:

- **Satellite:** Landsat 8
- **Acquisition Dates:**  
  - 29 April 2014  
  - 08 May 2014
- **WRS Path/Row:** 138/43 and 139/43

The data were obtained from **USGS EarthExplorer**.

---

## Methodology

The maps were generated using **remote sensing and GIS techniques**.

### Processing Steps

1. Acquisition of Landsat-8 satellite imagery
2. Radiometric and atmospheric preprocessing
3. Extraction of spectral bands
4. Calculation of environmental indices:
   - **Land Surface Temperature (LST)**
   - **Normalized Difference Water Index (NDWI)**
5. Spatial visualization and map preparation

---

## Coordinate System

- **Datum:** WGS 1984  
- **Projection:** Transverse Mercator  
- **UTM Zone:** 45N  
- **Units:** Meter  

---

## Tools & Software

The analysis and map preparation were conducted using:

- **ArcMap (ArcGIS Desktop)**
- Remote sensing raster processing tools
- GIS spatial analysis tools
- Cartographic visualization techniques

---

## Repository Contents

```
LST_NDWI
│
├── LST_NDWI_Map.jpg   # LST and NDWI spatial distribution map
├── README.md          # Project documentation
└── LICENSE            # MIT License
```

---

## Author

**Md. Habibullah Masbah**  
Undergraduate Student  
ID: 2107046  
Department of Urban & Regional Planning  
Rajshahi University of Engineering & Technology (RUET), Bangladesh

---

## License

This project is licensed under the **MIT License**.

See the [LICENSE](LICENSE) file for more details.
