# Soil Evaporation Simulation

This repository contains a Python simulation of soil evaporation using the soil evaporation capacitance model. It was developed to support the manuscript titled *[Your Manuscript Title]*.

## Repository Structure

soil-evaporation-simulation/
├── README.md
├── LICENSE
├── requirements.txt
├── .gitignore
├── data/
│   ├── soil_param_related.xlsx
│   └── Infiltration_output/
│       └── all_events_after_split/
│           ├── 2011/
│           │   ├── Dunes.shp
│           │   ├── Alluvium.shp
│           │   ├── Hard Limestone.shp
│           │   └── Karstified Limestone.shp
│           ├── 2018/
│           │   └── … (same structure as 2011)
│           └── 2020/
│               └── … (same structure as 2011)
├── results/
│   └── Soil_vol.xlsx    # (if generated externally)
└── src/
    └── soil_evaporation_simulation.py
