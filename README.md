# SpaceX Falcon 9 – Interactive Map with Folium

This repository contains the **Interactive Visual Analytics** stage of the IBM Data Science Professional Certificate Capstone Project.

The notebook demonstrates how interactive geographic visualizations can be created using **Folium** to explore SpaceX Falcon 9 launch sites and their surrounding infrastructure.

---

# Learning Objectives

After completing this notebook, you will be able to:

- Create interactive maps using Folium.
- Display launch sites on a geographic map.
- Add interactive markers and popups.
- Visualize launch site locations using circle markers.
- Measure distances between launch sites and nearby infrastructure.
- Interpret geographic patterns within launch data.

---

# Project Overview

Geographic location plays an important role in launch operations.

This notebook visualizes Falcon 9 launch sites on an interactive map and investigates nearby geographical features such as coastlines, railways, highways, cities, and launch facilities.

Interactive mapping provides an intuitive way to understand launch site environments that cannot be observed from tabular data alone.

---

# Dataset

The notebook uses launch site coordinates obtained during previous stages of the SpaceX Capstone Project.

The dataset includes:

- Launch Site
- Latitude
- Longitude
- Launch Success
- Landing Outcome

---

# Interactive Map Features

The Folium map includes the following components:

### Launch Site Markers

- Interactive markers
- Tooltips
- Popups
- Launch site information

### Geographic Visualization

- Circle markers
- Color-coded launch locations
- Interactive zoom and navigation

### Distance Analysis

The notebook also visualizes nearby infrastructure, including:

- Coastlines
- Railways
- Highways
- Cities

Distance calculations help evaluate the geographic suitability of each launch location.

---

# Technologies Used

- Python
- Pandas
- Folium
- Geopy
- Jupyter Notebook

---

# Workflow

```text
Launch Dataset
        │
        ▼
Launch Coordinates
        │
        ▼
Interactive Folium Map
        │
        ├── Markers
        ├── Circle Markers
        ├── Popups
        ├── Tooltips
        ├── Distance Calculation
        └── Geographic Layers
        │
        ▼
Interactive Geographic Analysis
```

---

# Learning Outcomes

After completing this project, you will be able to:

- Build interactive maps with Folium
- Display geographic information
- Create interactive map objects
- Perform basic geographic analysis
- Interpret spatial relationships within datasets

---

# Repository Structure

```text
.
├── spacex-interactive-map-folium.ipynb
└── README.md
```

---

# Related Capstone Modules

This repository is one stage of the complete SpaceX Falcon 9 Data Science pipeline:

- Data Collection (API)
- Web Scraping
- Data Wrangling
- Exploratory Data Analysis
- SQL Analysis
- **Interactive Map with Folium** ← current repository
- Plotly Dash Dashboard
- Predictive Modeling

---

# Author

**Aliona Vataman**

IBM Data Science Professional Certificate
