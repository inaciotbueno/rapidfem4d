# 🌿 RapidFEM4D: Aboveground Biomass Density Maps for Post-Hurricane Ian Forest Monitoring in Florida

## 📌 Overview
**RapidFEM4D** is a project focused on generating **Aboveground Biomass Density** maps to monitor the impact and recovery of Florida’s forests following **Hurricane Ian**. Using **Google Earth Engine (GEE)** and **machine learning models**, the project integrates **GEDI, Harmonized Landsat Sentinel, Sentinel-1** data to produce high-resolution biomass estimates.

## 📍 Study Area
- **Region:** Florida, USA  
- **Event Monitored:** **Hurricane Ian (2022)**
- **Key Data Sources:** 
  - **GEDI L4A** (Global Ecosystem Dynamics Investigation)
  - **Harmonized Landsat Sentinel**
  - **Sentinel-1**

## 🛠️ Project Components
### 🔹 **AGBD Model Development**
- Uses **Random Forest Regression** to train biomass models.
- Feature selection from **optical, radar, and LiDAR** data.
- Stored in **Google Earth Engine assets**
