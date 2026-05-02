
# GIS & Geospatial Analysis Portfolio

## 🛠 Tools & Skills

- **GIS Software:** ArcGIS Pro (active), QGIS (familiar)
- **Spatial Analysis:** NDVI, IDW interpolation, coordinate projection, species distribution modeling
- **Coordinate Systems:** NAD 1983 UTM Zone 10N, WGS 84
- **Statistical/ML for Geospatial:** Random Forest classification, scatterplot analysis
- **Programming:** Python, C++, SQL (Flask + SQLAlchemy backend experience)
- **Cartography:** Map layout design, multi-frame composition, legend/scale/north arrow conventions

---

##  Featured Projects

### 1. Smart Farm Site Analysis — UC Merced *(In Progress)*

**Course:** [Course code, e.g., ENGR 1XX] · **Tool:** ArcGIS Pro

A multi-checkpoint geospatial analysis of an agricultural Smart Farm site. The project applies remote sensing and interpolation techniques to assess vegetation health and soil characteristics across the parcel.

**Checkpoint 1 — Project Setup & Spatial Foundation** ✅
- Imported multi-source datasets (imagery, soil samples, parcel boundaries) into a managed ArcGIS Pro project
- Reprojected all layers to **NAD 1983 UTM Zone 10N** to ensure accurate distance and area measurements for the California study area
- Validated spatial alignment and built a clean working geodatabase

**Checkpoint 2 — Analysis** 🚧
- **NDVI analysis** from multispectral imagery to map vegetation vigor across the site
- **Inverse Distance Weighting (IDW) interpolation** of point soil samples to produce continuous soil-property surfaces
- **Scatterplot analysis** to investigate relationships between NDVI and soil variables

*Screenshots:*
<img width="3300" height="2550" alt="farm_overview" src="https://github.com/user-attachments/assets/559ebb4a-198a-4600-9237-52c31befb44e"



### 2. Bigfoot Species Distribution Model

**Tool:** ArcGIS Pro · **Method:** Random Forest

A species distribution model (SDM) predicting suitable habitat for *Sasquatch* sightings across the contiguous U.S., built as part of an environmental engineering lab.

**What I did:**
- Prepared occurrence records and environmental predictor rasters (climate, elevation, land cover) at consistent resolution and projection
- Trained a **Random Forest classifier** to predict habitat suitability across the study area
- Designed a **multi-frame map layout** showing the prediction surface, training data overlay, and inset locator map
- Troubleshot **linked Map Frame** behavior and refined symbology, legend, and labels for a publication-ready figure
- Wrote up the lab report addressing model assumptions, predictor importance, and limitations of presence-only data

*Screenshots:*


---

##  Why This Translates to QGIS

ArcGIS Pro and QGIS are **conceptually 1:1** for the operations in these projects:

| ArcGIS Pro | QGIS Equivalent |
|---|---|
| Geoprocessing pane | Processing Toolbox |
| Spatial Analyst (NDVI, IDW) | Raster Analysis / SAGA / GRASS |
| Layouts | Print Layout |
| Map Frames | Map items in Print Layout |
| Geodatabase | GeoPackage / SpatiaLite |
| ModelBuilder | Graphical Modeler |

The **spatial reasoning, projection awareness, and analytical workflow** transfer directly. I'm comfortable picking up QGIS's specific UI on a short ramp.
