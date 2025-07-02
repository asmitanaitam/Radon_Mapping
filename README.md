# 🧪 Radon Risk Mapping using Sentinel-2 Imagery

This project visualizes EPA Radon Zones overlaid on satellite imagery for Georgia, USA. It combines geospatial data with Google Earth Engine and satellite data using `geemap` and `leafmap`.

## ✅ Features
- Extracted Sentinel-2 imagery for a region of interest (Atlanta)
- Cleaned and merged EPA radon zone data by county
- Created interactive maps to visualize radon risk zones
- Exported final data to GeoJSON

## 🧰 Tools Used
- Python
- geemap, leafmap, folium, geopandas
- Google Earth Engine
- Sentinel-2 imagery
- EPA Radon Zone dataset

## 📁 Folder Structure
project/
├── data/ # Shapefiles, GeoJSONs, Excel
├── Radon_Mapping.ipynb 
├── README.md
├── requirements.txt
└── radon_zones_by_county.geojson

