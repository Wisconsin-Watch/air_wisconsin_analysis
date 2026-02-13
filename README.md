# Air Wisconsin: A Spatial Analysis of Changing Flight Corridors

This interactive scrollytelling project visualizes the operational shift in Air Wisconsin's flight paths between late 2025 and early 2026. By overlaying ADS-B flight data with federal detention infrastructure, this map explores the emergence of a specialized logistics chain.

## 🔗 Live Link
[View the Interactive Map](https://yourusername.github.io/air-wisconsin-analysis/)

## 📊 The Data
This project utilizes two primary data streams:

1. **Flight Telemetry:** Sourced via [ADS-B Exchange](https://www.adsbexchange.com/). This includes:
   - **Historical Network:** Sept 2025 – Jan 8, 2026 (Pre-reorganization).
   - **Current Network:** Jan 9, 2026 – Present (Post-reorganization).
2. **Infrastructure Data:** Sourced via **ICE Average Daily Population (ADP)** reports (October 2025). This dataset identifies facility locations and their reported detainee capacity.

## 🛠️ Technology Stack
- **Mapbox GL JS:** For high-performance vector map rendering.
- **Scrollama.js:** To handle the "scrollytelling" triggers and scroll-bound animations.
- **GeoJSON:** For geographic data storage.

## ⚖️ Methodology
Flight paths were aggregated by frequency between specific nodes. The "Shadow Map" section uses a spatial join to highlight correlations between high-frequency flight corridors and detention facility density. 

## 📝 Credits
Produced for **Wisconsin Watch**.
- **Data Processing:** [Your Name]
- **Visualization:** [Your Name]
- **Source:** ADS-B Exchange & ICE public records.
