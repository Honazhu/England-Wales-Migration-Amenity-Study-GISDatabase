# England and Wales Amenity GIS Database

This repository contains processed GIS datasets of various amenities in England and Wales, intended for spatial econometric research on migration patterns. And the data for the dataset is from the Geofabrik 1st Jan 2023 OSM file.

---

## 🗂 Data Structure

### 🚆 **Railway Amenities**
- **Railway Stations** (`railway_station_ew.geojson`)
- **Rail Tracks** (`railway_railtrack_ew.geojson.zip`) *(compressed due to file size limitations)*

**Note:** Railway amenity data have been cleaned and validated to ensure spatial continuity.

### 🏢 **Modern Amenities**
- Airports (`airport_ew.geojson`)
- Banks (`bank_ew.geojson`)
- Cinemas (`cinema_ew.geojson`)
- Commercial Complexes (`commerical_ew.geojson`)
- Fire Stations (`firestation_ew.geojson`)
- Hospitals (`hospital_ew.geojson`)
- Police Stations (`policestation_ew.geojson`)
- Schools (`school_ew.geojson`)
- Stadiums (`stadium_ew.geojson`)

**Note:** Modern amenities originally derived from shapefiles have been processed to ensure continuous spatial features from previously disconnected points.

---
## 📚 How to Cite

If you use this dataset in your research, please cite the following preprint:

> Zhu, Hona (2025). *Railway, Amenities, and Internal Migration: A Spatial Econometric Analysis in England and Wales*. SSRN. [https://doi.org/10.2139/ssrn.5354053](https://doi.org/10.2139/ssrn.5354053)

---

## Data Source & License

- Original data sourced from [Geofabrik](https://download.geofabrik.de/), based on [OpenStreetMap](https://www.openstreetmap.org) data licensed under [Open Database License (ODbL)](https://opendatacommons.org/licenses/odbl/1-0/).

- Derived datasets in this repository are licensed under the [ODbL](LICENSE.md).


---

## 📧 Contact

For any inquiries or collaboration, please contact: [academic@honazhu.com].
