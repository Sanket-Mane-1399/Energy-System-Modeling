# 🇪🇸 100% RES Model for Spain  

This repository contains a power system model of Spain designed to explore pathways to a **100% renewable energy system**. The model integrates high-resolution weather and demand data with geospatial analysis to evaluate the feasibility of fully decarbonized electricity supply.  

## Overview  

The project combines **climate reanalysis data, GIS-based resource assessment, and power system optimization** to answer the question:  

> Can Spain reliably meet its electricity demand using only renewable resources?  

## Key Features  

- **Time-Series Resource Modeling**  
  - Analyzed hourly ERA5 data to model **solar PV and wind generation** across seasons.  

- **Geospatial Site Assessment**  
  - Conducted **GIS-based spatial analysis** to identify optimal renewable energy sites, accounting for resource potential, land-use restrictions, and grid proximity.  

- **Power System Optimization**  
  - Built a **PyPSA-based power system model** simulating network flows and constraints using real demand data.  
  - Optimized capacity expansion and dispatch decisions to minimize costs.  

- **Advanced Solver Integration**  
  - Used the **Gurobi solver** for efficient large-scale optimization.  
  - Performed **sensitivity analyses** to explore trade-offs and strategies for reducing capital expenditures (CAPEX).  

## Tech Stack  

- **Python**: Data analysis and model integration  
- **PyPSA**: Power system modeling and optimization  
- **Gurobi**: Optimization solver  
- **GIS Tools**: Spatial analysis of renewable potential  
- **ERA5**: High-resolution weather and climate data  
