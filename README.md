# Florida Utility Pipeline & Community Resilience Analysis

### [🔗 View Live Interactive Pipeline & Resilience Map](https://www.arcgis.com/apps/mapviewer/index.html?webmap=4312d7f79e90415f9318ca482c4e0b79)

## Project Overview
This project performs a spatial vulnerability assessment of Florida’s gas transmission network. By integrating interstate and intrastate pipeline data with the FEMA Community Resilience Challenges Index (CRCI), this analysis identifies specific infrastructure segments passing through high-risk or underserved communities.

## Technical Highlights
* **Spatial Join Analysis:** Performed a robust spatial intersection between linear utility assets and county-level resilience polygons to physically enrich the pipeline attribute table with CRCI metrics.
* **Enhanced Data Architecture:** Transitioned from dynamic calculations to a joined data model, allowing for high-performance labeling and advanced attribute filtering.
* **Cartographic Hierarchy:** Developed custom labeling logic using Arcade to display localized risk percentages, utilizing scale-dependency to maintain map clarity across different zoom levels.
* **Authoritative Integration:** Synthesized **U.S. Energy Information Administration (EIA)** pipeline data with **FEMA** CRCI datasets.

## Preview
<img width="1842" height="867" alt="Florida Pipeline Resilience Map" src="https://github.com/user-attachments/assets/0247b543-b8fc-4b02-8169-3ffd7b7b98c5" />

## Data Sources
* U.S. Energy Information Administration (EIA)
* Federal Emergency Management Agency (FEMA)

**Analysis by Leonard Sala.**
