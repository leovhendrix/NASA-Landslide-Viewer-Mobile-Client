# 🌍 TerraWatch

**TerraWatch** is a remote sensing application for monitoring, visualizing, and analyzing landslide activity around the world. It brings satellite-derived hazard data into a simple, accessible interface so that researchers, disaster-response teams, and the public can understand where landslide risk is emerging in near real time.

![Landslide remote sensing visualization](https://svs.gsfc.nasa.gov/vis/a020000/a020200/a020226/landslide_seq_00660_print.jpg)

*Image credit: NASA Goddard Space Flight Center, Scientific Visualization Studio*

---

## 🔎 Overview

Landslides are one of the most underreported natural hazards worldwide, causing thousands of fatalities and billions of dollars in damage every year. TerraWatch was built to make landslide-hazard data easier to explore by combining:

- Remote sensing imagery and geospatial hazard layers
- Historical and time-aware landslide event data
- A clean frontend for querying, filtering, and visualizing landslide activity by region and date

## 🛰️ Backend / Data Source

TerraWatch's backend is powered by the **[NASA Landslide Viewer](https://landslides.nasa.gov/viewer)**, part of NASA's Global Landslide Catalog (COOLR) infrastructure. This provides:

- A global, time-aware catalog of landslide events
- Satellite and precipitation-based triggers (e.g., rainfall data from the Global Precipitation Measurement mission)
- Historical landslide records compiled from media and citizen-science reports

TerraWatch queries and layers this data to power its own visualization and analysis tools on top of NASA's open geospatial infrastructure.

## ✨ Features

- 🗺️ Interactive map view of landslide events by location and time
- 📊 Historical trend analysis of landslide frequency and severity
- 🌧️ Correlation of landslide events with rainfall and precipitation data
- 🔔 Region-based hazard awareness for disaster-response teams

## 📄 License

This project uses publicly available NASA Earth science data. NASA data are open and freely available; please review NASA's [data and reproduction guidelines](https://www.nasa.gov/multimedia/guidelines/index.html) when reusing imagery or datasets.

---

## 🏢 Organization

**STARK HELIX**

Built by **Surafel Gashaw** ( **Leo Vance Hendrix**)
