# Rice Map – Gummawala (Kharif 2024)

This repository hosts an interactive rice classification map for the **Gummawala region**, Uttarakhand, during the **Kharif 2024** cropping season. The project combines **Sentinel-2 satellite imagery**, **object-based classification**, and **machine learning** to delineate rice-growing parcels and estimate potential yields.

🔗 **Explore the live map**:  
 [https://goswamishreyas.github.io/Rice-map-gummawala/](https://goswamishreyas.github.io/Rice-map-gummawala/)

---

## Why Rice Mapping?

Rice is the dominant Kharif crop in Gummawala and across the Haridwar district, typically sown in **June-July** and harvested by **October-November**. With increasing emphasis on **precision agriculture**, satellite-based monitoring helps:
- Identify rice-growing fields
- Assess crop health
- Predict yield variation
- Enable targeted interventions for water and fertilizer management

According to regional agricultural statistics, **average rice yields** in Uttarakhand range between **2.2 to 3.2 tonnes/ha**, with variations depending on irrigation, seed variety, and agronomic practices.

---

## Classification Methodology

### Object-Based Classification (OBC)

Unlike traditional **pixel-based classification**, which can result in noisy outputs and overfitting, **object-based classification**:
- Segments the imagery into **meaningful field parcels** (objects)
- Extracts **spectral**, **textural**, and **geometrical** features
- Classifies the entire object (field) as rice or non-rice using machine learning

This approach closely mimics how humans interpret satellite imagery and is especially effective in **agricultural landscapes with well-defined boundaries**.

### Yield Estimation Using Machine Learning

- **Peak NDVI** (around mid-season) was used for the crop growth representation during the season.
- A **machine learning model** trained on field data was used to estimate parcel-level rice yield.

---

## Features

- 🌍 **Interactive Leaflet Map**
- 🧭 Base layers: **OpenStreetMap** and **Google Satellite**
- 🗂️ **GeoJSON layers** for classified rice fields and yield estimates
- 🌾 Clickable field parcels to view predicted **yield**

---
